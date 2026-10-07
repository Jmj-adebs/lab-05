# CMPUT 301 : Lab 5 Participation Exercise

## Student Details

- **Full Name:** Oluwajomiloju Adebisi-Olusola
- **CCID:** adebisio

## References and Resources
https://www.geeksforgeeks.org/kotlin/kotlin-programming-language/

Claude(AI)
Prompt: How do I display a confirmation box after delete button is selected in kotlin?
Answer:
AlertDialog(
            onDismissRequest = { showDialog = false },
            title = { Text("Delete item") },
            text = { Text("Are you sure you want to delete this? This action cannot be undone.") },
            confirmButton = {
                TextButton(onClick = {
                    onConfirmDelete()
                    showDialog = false
                }) {
                    Text("Delete")
                }
            },
            dismissButton = {
                TextButton(onClick = { showDialog = false }) {
                    Text("Cancel")
                }
            }
        )

## Verbal Collaboration

| Student Name | CCID      |
| ------------ | --------- |
| `student`    | `student` |
| `<Add more>` | `<CCID>`  |
