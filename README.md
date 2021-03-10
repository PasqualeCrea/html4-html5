# html4-html5
## Convert HTML4 to HTML 5
1. Change the <!DOCTYPE> declaration from HTML 4.01 to the appropriate HTML5 declaration. This change will make the W3C validator check the file for HTML5 compliance, not HTML 4.01 compliance. Save the NotValid.html file.
1. Browser: Access the W3C Markup Validation Service page.
1. Click the Validate By File Upload link, click Choose File and navigate to the Lesson02\Optional_Lab_2-1\ folder. Select the Not Valid.html file you just modified, then click the Open button. The name of the file you want to upload will appear in the File field.
1. Click the Check button.
1. **Instructor Note:** The validator often returns only one error at a time, especially for fatal problems such as a missing DTD. After students resubmit their edited files, they will begin to see that the validation service returns multiple errors. The validator often approximates the location of an error, rather than identifying the exact location.
1. When the validation service finishes reviewing the document, a results window will open and report how well the document complied with HTML5.
1. Take a few moments to read the results. As you read, see if you can determine what types of errors might exist. For example, a major problem is the <meta> tag. HTML5 is simplified, so only the charset attribute is required in the <meta> tag. The older, unnecessary attributes create many validation errors.
1. Using an Editor, examine NotValid.html and consider the results you received from the validator. Make the changes necessary so the file complies with the rules you have learned for HTML5 documents.
1. Reload the document in the markup validator and validate it again to see if you have corrected all the errors. The validator results window should indicate that the code is valid HTML5. If you still have errors, open the file in VS Code, correct the errors, then validate the file again. Repeat this process until you have corrected all the errors.
1. After your file is validated by the service, rename the document valid.html.
