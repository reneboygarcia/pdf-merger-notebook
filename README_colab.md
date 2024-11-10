# Simple PDF Merger Tool

This tool helps you merge multiple PDF files into a single PDF document. It's designed to be easy to use, especially in Google Colab!

## 🚀 Quick Start (Google Colab)

1. Open this notebook in Google Colab: [Open in Colab](https://colab.research.google.com/github/reneboygarcia/pdf-merger/blob/main/pdf_merger.ipynb) 
   
2. Install required package:
   - Click on the first code cell and run: `!pip install PyPDF2`

3. Upload your PDF files:
   - Click on the folder icon on the left sidebar
   - Create a folder named `sample_input`
   - Upload your PDF files to this folder

4. Run the merger:
   - Run all cells in the notebook
   - Your merged PDF will be saved in the `sample_output` folder

## 📝 How to Use

1. **Basic Merging (Default)**
   - Files will be merged in alphabetical order
   - Just run the code as is!

2. **Custom Order Merging**
   - Uncomment the `custom_order` line in the last cell
   - Modify the list with your PDF filenames in desired order
   - Example: `custom_order = ["second.pdf", "first.pdf"]`

## ⚠️ Important Notes

- Make sure all your PDFs are in the `sample_input` folder
- The merged file will be saved as `merged_output.pdf` in the `sample_output` folder
- Download your merged PDF from the files panel before closing Colab

## 🆘 Need Help?

If you run into any issues, check that:
1. All your PDFs are properly uploaded
2. File names match exactly if using custom order
3. You've installed PyPDF2 package
