# ps-host-check

<!-- wp:paragraph {"textColor":"secondary"} -->
<p class="has-text-color has-secondary-color">Say you need to test the connectivity for a series of computers in your network. Here's a script you can use to do just that using powershell and a CSV file as input. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"textColor":"secondary"} -->
<p class="has-text-color has-secondary-color">You first need to create the csv file with the names of the hosts you want to test and the columne name needs to be <strong><span style="text-decoration:underline;">ComputerName</span></strong> and save it as hostslist.csv. </p>
<!-- /wp:paragraph -->

<!-- wp:paragraph {"textColor":"secondary"} -->
<p class="has-text-color has-secondary-color">The results will also be placed in a file called hostsoutput.csv ( the script will append the details, so if you run it multiple times, it will not overwrite, but append to the end of the file.  </p>
<!-- /wp:paragraph -->
