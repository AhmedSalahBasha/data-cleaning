<h1>data-cleaning</h1>

<ol>
<h3><li>Dataset</li></h3>
  We have a relational address dataset with the following schema:<br>
  <b>S(RecID; FirstName;MiddleName; LastName; Address; City; State;ZIP; POBox; POCityStateZip; SSN; DOB)</b>

<h3><li>Tasks</li></h3>
  There are some desired data quality constraints for the dataset:
  <ol>
    <li>All alphabetical characters in all columns should be capitalized.</li>
    <li>Address data should be compatible to the standard in https://tools.usps.com/go/ZipLookupAction!input.action.</li>
    <li>The State column should contain the correct two character US state code.</li>
    <li>City column should contain real city names.</li>
    <li>ZIP column should be formatted as a 5 digit value.</li>
    <li>SSN column should contain an 8-10 digit value.</li>
  </ol>
  
Note that, you do not need to fix the DOB, POBox, and POCityStateZip columns.

</ol>
