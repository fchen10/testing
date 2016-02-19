# testing
| Test ID| Description | Expected Result | Actual Result |
| ------------- | ----------------------- | -------------------------------------------------- | ----------- |
| Bug 1 | _Preconditions: <br>_ Admin (MID: 9000000001, Password: pw) and HCP Kelly Doctor (MID: 9000000000, Password: pw) exists in iTrust <br /> _Step_: <br> 1. Login as Admin <br> 2. Click Edit Personnel from the sidebar. <br> 3. Enter Kelly as first name and Doctor as last name. <br> 4. Click User Enter then choose the user. <br> 5. In the new page we can see dropdown for editing speciality. | Speciality is dropdown box not the free enter text.|
| Bug 2 | _Preconditions: <br>_ Patient 2 (MID: 2, Password: pw) exists in iTrust <br /> _Step_: <br> 1. Login as patient 2 <br> 2. Click View My Records from the sidebar. <br> 3. Choose Complete Visit Survey for Jun 10, 2007  <br> 4. Enter 5 for waiting room and 10 for examination room. <br> 5. Copy the url and then click submit button. <br> 6. Paste the url | Error message "iTrust - Error You have already taken this survey, you cannot take it again." display. |

