# Writing Good Documentation

## Step 1 - Using Codeblocks.

Codeblocks in markdown make it *very easy* for tech people to **copy, paste, share** code. A good _Cloud Engineer_ uses Codeblocks whenever possible.

Because it allows others to copy and paste their code to replicate or research issues.

- In order to create codeblocks in markdown you need to use three backticks (`)
- Not to be confused with single quotation (')

```
# Define an array of numbers
numbers = [1, 2, 3, 4, 5]

# Initialize a variable to store the sum
sum = 0

# Loop through the array and calculate the sum
numbers.each do |num|
  sum += num
end

# Print the result
puts "The sum of the numbers is: #{sum}"

With backticks
```

- When you can you should attempt to apply syntax highlighting to you codeblocks

 ```ruby
 # Define an array of numbers
numbers = [1, 2, 3, 4, 5]

# Initialize a variable to store the sum
sum = 0

# Loop through the array and calculate the sum
numbers.each do |num|
  sum += num
end

# Print the result
puts "The sum of the numbers is: #{sum}"
```

Make note of where the backtick button is located.
It should appear above the tab key, but it may vary based on your keyboard layout.


<img width="550px" alt="backtick-key" src="https://github.com/awkamara/github-docs-example/assets/145500282/04c41d47-ee85-4143-9983-913ae7c677dd">

Good Cloud Engineers use codeblocks for both Code and Errors that appear in the console.



```bash
Traceback (most recent call last):
  File "<your_script_name>", line 2, in <module>
    undefined_variable = some_variable + 5
NameError: undefined local variable or method `some_variable' for main:Object
```

> Here is an example of using a codeblock for an error that appears in bash.

## Step 3 - Use Github Flavored Markdown Task Lists

Github extends Markdown to have a list where you can check off items. <sup>[1]</sup>](#external-references)


- [x] Finish Step 1
- [ ] Finish Step 2
- [x] Finish Step 3

# Step 4 - Use Emojis (Optional)

GitHub Flavored Markdown (GFM) supports emoji shortcodes.
Here are some examples:

| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | `:cloud_with_lighting:` | 🌩️ |

# Step 5 how to create a table


You can use the following markdown format to create tables:

```md
| Name | Shortcode | Emoji |
| --- | --- | --- |
| Cloud | `:cloud:` | :cloud: |
| Cloud with lighting | `:cloud_with_lighting:` | 🌩️ |
```
 Github extends the functionality of Markdown tables to provide alignment and table cell formatting option. [<sup>[2]</sup>](#external-references)
 
 
 ## External References

- [Github Flavored Markdown Spec](https://github.github.com/gfm/) 
- [Bsic writing and formatting syntax (Github Flavored Markdown)](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#quoting-text) 
- [GFM - Task List](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#task-lists) <sup>[1]</sup>
- [GTM - Emoji CheatSheet](https://github.com/ikatyang/emoji-cheat-sheet)
- [GFM - Tables (with extensions)](https://github.github.com/gfm/#tables-extension-) <sup>[2]</sup>  
