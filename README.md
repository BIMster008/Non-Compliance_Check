# Non-Compliance Check
A Python Script constructed to find all unwanted Properties and their PropertySets of an IFC Schema.

Did you ever get bothered by too much information in the IFC schema?
Did you ever get annoyed by those repeating properties in serveral Psets?
I did :)

Therefore, I have created this python script, which you can execute in BonsaiBIM to check your IFC schema.

# What is needed!
In the first step, you will need to define your "allowed" properties and PropertySets in an IDS file. Here you define every property that should be includede in the IFC file, therefore the IDS is going to work as a filter to filter out everything that is not allowed.
Secondly, you will need an IFC file to test it against the Non-Compliance Check

# How to use it?
1. Install Blender and the BonsaiBIM add-On
2. Take the Non-Compliance Check Python script and paste it into Blender
3. In the lower part of the script define the path and file name of a) IFC File, b) IDS File, c) HTML Debug and c)Output of the HTML result from the Non-Compliance Check
4. Run the Script

# Results
If the script does not encounter any errors, an HTML page with the results will open.
The result is going to be a list of Properties and PropertySets that are not included in the IDS. In the list you will be able to identify all the unwanted information being generated by all those native sofwtares.

Since I have generated this first Python script with the help of ChatGPT 4o, I would appreciate any valuable hints and tricks to improve this checking.
Thank you
