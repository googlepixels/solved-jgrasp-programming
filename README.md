Download Link: https://assignmentchef.com/product/solved-jgrasp-programming
<br>
<ol>

 <li>The 1st step is to make your CSV file. Open up jGRASP. Cick: File, New, Plain Text, to create a new text file. Then, save the file as a CSV file by adding the .csv file extension when you save it: filename.csv Otherwise, open up a CSV excel file and type in your data. The 1st row should be the column names, separated by commas. The 2nd row, 3rd row, etc. should be the data from Assignment #2. Add a little more data, so you have at least 10 rows of data. Here is an example CSV file from the grocery list program: <a href="https://www2.hawaii.edu/~walbritt/ics211/assignments/groceries.csv">csv</a>. And here is an exaple CSV file from my “Marine Mammals of Hawai’i” example: <a href="https://www2.hawaii.edu/~walbritt/ics211/assignments/mammals.csv">mammals.csv</a>** Make sure you submit your CSV file with your assignment. **</li>

 <li>The 2nd step is to write your program! Here is starter code: <a href="https://www2.hawaii.edu/~walbritt/ics211/assignments/LastnameFirstname09.java">LastnameFirstname09.java</a> You will have two classes – your <strong>public class LastnameFirstname09</strong> and <strong>class </strong>HawaiiNativeBirds** The <strong>class </strong>HawaiiNativeBirds does NOT have the public modifier. **** The <strong>class </strong>HawaiiNativeBirds is NOT nested inside <strong>public class LastnameFirstname09</strong>. **** The <strong>class </strong>HawaiiNativeBirds is a class definition, which contains the variables (data fields) and methods to define objects, which store data. **</li>

 <li><strong>class </strong>HawaiiNativeBirds is the type of data that you stored in your input file. For example, I am using “Marine Mammals of Hawai’i”, so my class is: <strong>class </strong>HawaiiNativeBirds</li>

 <li>The 1st commandline argument (args[0]) is the name of your input file that you just created. Have some error checking to make sure there is only one command argument.</li>

 <li>In your main() method, make an array of objects of class HawaiiNativeBirds. Display the array on the screen – it should be all nulls at this point.</li>

 <li>The next step is to initialize the array with the data from the file. Earlier this semester, we read a file and stored it in an array with this program: <a href="https://www2.hawaii.edu/~walbritt/ics211/examples/ArrayBasedGroceryList.java">ArrayBasedGroceryList.java</a></li>

 <li>Before we store data in our array of objects, we have to create data fields, a constructor, and toString() method for <strong>class </strong>HawaiiNativeBirds.</li>

 <li>Below your <strong>public class LastnameFirstname09</strong> class, create data fields, a constructor, and toString() method for <strong>class </strong>HawaiiNativeBirds.</li>

 <li>Create three data fields – one data field for each of the attributes, which is the same as the three column names, in your <strong>class </strong>HawaiiNativeBirds. For example, for my <strong>class </strong>HawaiiNativeBirds, I have these data fields: name, population, and length.</li>

 <li>Write the constructor for your <strong>class </strong>HawaiiNativeBirds. You should have a three parameters, which initialize your three data fields. For example, I have three parameters of type String, Integer, and Double in my constructor.</li>

 <li>Write the <strong>toString()</strong> method for your <strong>class </strong>HawaiiNativeBirds. The return value should return a String with the three data fields, so they can be displayed.</li>

 <li>See <a href="https://www2.hawaii.edu/~walbritt/ics211/examples/PresidentDriver.java">PresidentDriver.java</a> for an example of a class, constructor, toString() method, and an array of objects.</li>

 <li>The next step is to make get() and set() methods, so you can change each data field as you wish. You should have three (3) get() methods – one get() method for each data field. And you should have three (3) set() methods – one set() method for each data field.Or, you can make a single method that also updates each data field. You should have three (3) methods – one method for each data field you are updating.</li>

 <li>After you make the changes to your data fields for each element, print the array of HawaiianTheme objects to the screen again.</li>

 <li>See <a href="https://www2.hawaii.edu/~walbritt/ics211/examples/PresidentDriverWithMethods.java">PresidentDriverWithMethods.java</a> for an example of a class, constructor, toString() method, an array of objects, get() methods, set() methods, and other update methods.</li>

 <li>** The next step is to use inheritance to add a subclass to your <strong>class </strong>HawaiiNativeBirds, two more data fields, and two sets to get() and set() methods (or two updating methods) for the two data fields. **</li>

 <li>Here is starter code: <a href="https://www2.hawaii.edu/~walbritt/ics211/assignments/LastnameFirstname10.java">LastnameFirstname10.java</a> You will have three classes – your <strong>public class LastnameFirstname10</strong>, <strong>class </strong>HawaiiNativeBirds, and a <strong>class </strong>HawaiiNativeBirds<strong>WithMoreData</strong>, which is the subclass of <strong>class </strong>HawaiiNativeBirds. In the constructor for <strong>class </strong>HawaiiNativeBirds<strong>WithMoreData</strong>, you can use <strong>super(parameter1,parameter2,parameter3)</strong> to initialize the data fields of superclass <strong>class HawaiianTheme</strong>. Write the appropriate toString(), get(), set(), and/or other updating methods.</li>

 <li>Create two more columns in your CSV file. Any two more columns that make sense to your HawaiianTheme theme. For example, add the scientific name, or Hawaiian language name, or other appropriate data. For example, I added a genus and species for each marine mammal in my <a href="https://www2.hawaii.edu/~walbritt/ics211/assignments/mammals2.csv">HawaiiNativeBirds<strong>.csv</strong></a> CSV file.</li>

 <li>See <a href="https://www2.hawaii.edu/~walbritt/ics211/examples/PresidentDriverWithInheritance.java">PresidentDriverWithInheritance.java</a> for an example of a class, constructor, toString() method, an array of objects, get() methods, set() methods, and other update methods, with the additional subclass, and corresponding constructor, toString(), get(), set(), and other update methods. Note that your program will have an array of <strong>class </strong>HawaiiNativeBirds<strong>WithMoreData</strong>, which stores only HawaiiNativeBirds<strong>WithMoreData</strong> objects, but <a href="https://www2.hawaii.edu/~walbritt/ics211/examples/PresidentDriverWithInheritance.java">PresidentDriverWithInheritance.java</a> has a array of <strong>class President</strong>, so it can store both <strong>President</strong> objects and <strong>PresidentWithMiddleName</strong> objects. The task of your assignment is to store two more data fields in a subclass, so your program can process two more columns of data in your CSV file. The task of the <a href="https://www2.hawaii.edu/~walbritt/ics211/examples/PresidentDriverWithInheritance.java">PresidentDriverWithInheritance.java</a> program is to store presidents, some with middle names and some without middle names.</li>

</ol>

1.   Display MarineMammalsOfHawaii array[] without initializing elements:2.   index   element3.     0     null4.     1     null5.     2     null6.     3     null7.     4     null8.     5     null9.     6     null10.   7     null11.   8     null12.   9     null13.   10     null14.   11     null15.   12     null16.   13     null17.   14     null18.   15     null19.   16     null20.   17     null21.  22. Read from input file: mammals2.csv23.  24. Display MarineMammalsOfHawaii array[] after initializing elements:25. index   name                        population   length (meters) Genus species26.   0     Hawaiian monk seal               1100      2.40          Monachus schauinslandi27.   1     humpback whale                  10000     16.00          Megaptera novaeangliae28.   2     spinner dolphin                  3351      2.35          Stenella longirostris29.   3     common bottlenose dolphin         235      3.50          Tursiops truncatus30.   4     Risso’s dolphin                 85000      4.00          Grampus griseus31.   5     rough-toothed dolphin          150000      2.83          Steno bredanensis32.   6     striped dolphin               2000000      2.60          Stenella coeruleoalba33.   7     pygmy killer whale                817     20.50          Feresa attenuata34.   8     false killer whale                150      2.80          Pseudorca crassidens35.   9     melon-headed whale               2950      3.00          Peponocephala electra36.  10     short-finned pilot whale         8850      3.70          Globicephala macrorhynchus37.  11     sperm whale                      7082     17.30          Physeter macrocephalus38.  12     dwarf sperm whale               19000      3.00          Kogia sima39.  13     pygmy sperm whale                  50      3.50          Kogia breviceps40.  14     orca                               50     10.70          Orcinus orca41.  15     Blainville’s beaked whale        2200      5.00          Mesoplodon densirostris42.  16     Cuvier’s beaked Whale           13000      8.30          Ziphius cavirostris43.  17     pantropical spotted dolphin   3000000      2.50          Stenella attenuata44.  45. Display MarineMammalsOfHawaii array[] after changing data fields in each element:46. index   name                        population   length (feet)   Genus species47.   0     HAWAIIAN MONK SEAL               1101      7.87          MONACHUS SCHAUINSLANDI48.   1     HUMPBACK WHALE                  10001     52.49          MEGAPTERA NOVAEANGLIAE49.   2     SPINNER DOLPHIN                  3352      7.71          STENELLA LONGIROSTRIS50.   3     COMMON BOTTLENOSE DOLPHIN         236     11.48          TURSIOPS TRUNCATUS51.   4     RISSO’S DOLPHIN                 85001     13.12          GRAMPUS GRISEUS52.   5     ROUGH-TOOTHED DOLPHIN          150001      9.28          STENO BREDANENSIS53.   6     STRIPED DOLPHIN               2000001      8.53          STENELLA COERULEOALBA54.   7     PYGMY KILLER WHALE                818     67.26          FERESA ATTENUATA55.   8     FALSE KILLER WHALE                151      9.19          PSEUDORCA CRASSIDENS56.   9     MELON-HEADED WHALE               2951      9.84          PEPONOCEPHALA ELECTRA57.  10     SHORT-FINNED PILOT WHALE         8851     12.14          GLOBICEPHALA MACRORHYNCHUS58.  11     SPERM WHALE                      7083     56.76          PHYSETER MACROCEPHALUS59.  12     DWARF SPERM WHALE               19001      9.84          KOGIA SIMA60.  13     PYGMY SPERM WHALE                  51     11.48          KOGIA BREVICEPS61.  14     ORCA                               51     35.10          ORCINUS ORCA62.  15     BLAINVILLE’S BEAKED WHALE        2201     16.40          MESOPLODON DENSIROSTRIS63.  16     CUVIER’S BEAKED WHALE           13001     27.23          ZIPHIUS CAVIROSTRIS64.  17     PANTROPICAL SPOTTED DOLPHIN   3000001      8.20          STENELLA ATTENUATA65.  66.





