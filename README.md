# Step 1: Create input.txt with some sample lines (do this only once)
with open("input.txt", "w") as file:
    file.write("Python is powerful.\n")
    file.write("It is widely used in web development.\n")
    file.write("Data science relies heavily on Python.\n")
    file.write("Machine learning models are often built with it.\n")
    file.write("Python makes coding fun and productive.\n")

# Step 2: Read the contents of input.txt
with open("input.txt", "r") as file:
    content = file.read()

# Step 3: Count the number of words
word_count = len(content.split())

# Step 4: Convert text to uppercase
content_upper = content.upper()

# Step 5: Write processed text and word count to output.txt
with open("output.txt", "w") as file:
    file.write("Processed Text:\n")
    file.write(content_upper + "\n")
    file.write(f"\nWord Count: {word_count}\n")

# Step 6: Print success message
print("✅ File processed successfully! Check output.txt for results.")
# week-4-ass-plp-py
