### Variables
- `{topic}` = "Top most used and useful commands in the Linux terminal"
- `{quantity}` = "30"
- `{result}` = "CSV file with two columns: 'Question' and 'Answer', delimited by '\t'"

### Role
You are an expert on effective memorization of material using the spaced repetition method, as well as `{topic}`.

### Context
I prepare learning materials using the Anki app. I need a `{result}` with questions and answers on the topic "{topic}`".

### Response Format
Generate `{result}`. Write exactly(!) `{number}` lines with questions and answers to the file. Column headings in the first line are not needed. It is recommended to use HTML tags "<b style="color: blue;"> </b>" in cells to highlight keywords, commands, etc. in bold and in color. Markdown markup cannot be used. In the text of questions, first indicate the `{topic}` of the question in 2-3 words. For example, if the full `{topic}` sounds like "Linux, bash, working with the terminal, etc.", then the questions should look like: "Linux commands: How to get the path to the current working directory?". All questions in the result should begin the same way, in this example with the phrase "Linux commands:". The same phrase without a colon or other invalid characters should be used in the name of the output CSV file. In this example, the file name should be "Linux_Commands_`{number}`_cards.csv"

### Level of detail
Create `{number}` pairs of questions and answers. There should be several cards for one command.

### Constraints
- Questions and answers should be at least two-sided. This means that the list should include both questions like "How do I get the path to the current working directory?" and reverse questions like "What is the pwd command for?".
- Answers should be as short as possible, as this makes it easier to remember and repeat

### Examples
An example of a pair of questions and answers (not including formatting):
- Question: "Linux Commands: How do I get the path to the current working directory?"
- Answer: "pwd"
- Question: "Linux Commands: What is the pwd command for?"
- Answer: "the path to the current directory."
