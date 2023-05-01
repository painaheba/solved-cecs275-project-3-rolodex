Download Link: https://assignmentchef.com/product/solved-cecs275-project-3-rolodex
<br>
5/5 - (1 vote)

–

Create a class that represents a Contact (.h and .cpp). A Contact has a first name, last name, phone number, address, city, zip, and state, all stored as private strings. Make a constructor and get and set methods to change the Contact’s information. Overload the &lt; (compare by last name, then first name), == (first and last name), &lt;&lt;, and &gt;&gt; operators.

Use the Linked List class (.h and .cpp) given in lecture (normal or recursive). Modify the Node to store a Contact. Methods of the Linked List class should include: get, set, size, isEmpty, add (to end), remove (by last name, first name), remove (by index), sort, search (by last name, returns list of matches), search (by zip code, returns list of matches), search (by first and last name, returns a Contact). and an overloaded &lt;&lt; operator to display an enumerated list of Contacts in sorted order (by last name then first name).

In your main, create a Linked List and initially populate it with Contacts read in from the file ‘addresses.txt’. Allow the user to add, remove, search, modify, and display the list. When the user quits, write the updated list back to the file in the same format.

Create functions and menu options to:

<ol>

 <li>Add

  <ol>

   <li>add a Contact to the end of the list. Use the overloaded &gt;&gt; to input.</li>

   <li>ask the user enter the first and last name, then allow the user to input anyother information they have. If they do not enter a value for a particular field, store an empty string (check that a first and last name was entered).</li>

  </ol></li>

 <li>Remove

  <ol>

   <li>by first and last name – if found, then remove the Contact from the list.</li>

   <li>by index in the list – display the enumerated list (1 based), get the user’schoice, then remove the Contact at that location.</li>

  </ol></li>

 <li>Search

  <ol>

   <li>last name – display all information for each Contact with that last name.</li>

   <li>first and last name – display all of information for the matching Contact.</li>

   <li>zip-code – display all information for each Contact’s with that zip code.</li>

  </ol></li>

 <li>Update</li>

</ol>

a. prompt the user to enter the Contact’s full name. Then prompt the user to

enter which part of the Contact they’d like up update. Take in the updated information, and update the Contact’s data.

5. Displaya. display an enumerated list of all contacts alphabetically by last name, and

then first name.6. Quit – write back to the file when the user is finished.

Notes:

<ol>

 <li>Document all classes, methods, and functions (@params and @returns).</li>

 <li>You should have at least 5 files (.h’s and .cpp’s)</li>

 <li>Check all user input.</li>

 <li>Read and write to the same file. Write back in the same format.</li>

</ol>

Example Output:

<pre>Rolodex Menu:1. Add Contact2. Remove Contact3. Search for Contact4. Modify Contact5. Display Contacts6. Quit1</pre>

<pre>Add Menu:Enter First Name: BartEnter Last Name: SimpsonEnter Phone #: 555-1212Enter Address:742 Evergreen TerraceEnter City: SpringfieldEnter Zip-Code: 12345Enter State: IL</pre>

<pre>Rolodex Menu:1. Add Contact2. Remove Contact3. Search for Contact4. Modify Contact5. Display Contacts6. Quit3</pre>

<pre>Search Menu:A. Search by Full NameB. Search by Last NameC. Search by Zip-CodeB</pre>

<pre>Enter Last Name: Simpson</pre>

<pre>1. Bart Simpson   555-1212</pre>

<pre>   742 Evergreen Terrace</pre>

<pre>   Springfield 12345 IL2. Homer Simpson</pre>

555-1212

<pre>Rolodex Menu:1. Add Contact2. Remove Contact3. Search for Contact</pre>

<pre>4. Modify Contact5. Display Contacts6. Quit4</pre>

<pre>Enter First Name: HermanEnter Last Name: Munster</pre>

<pre>Herman Munster131-1313</pre>

<pre>Update Menu:A. Enter First NameB. Enter Last NameC. Enter Phone NumberD. Enter AddressE. Enter CityF. Enter Zip-CodeG. Enter StateQ. Save and QuitD</pre>

<pre>Enter Address:1313 Mockingbird Lane</pre>

<pre>Modify Menu:A. Enter First NameB. Enter Last NameC. Enter Phone NumberD. Enter AddressE. Enter CityF. Enter Zip-CodeG. Enter StateQ. Save and QuitQ</pre>

Saving…

<pre>Rolodex Menu:1. Add Contact2. Remove Contact3. Search for Contact4. Modify Contact5. Display Contacts6. Quit6</pre>