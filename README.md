# Random-Name-Generator

This simple application can generate random Nigeria names both firstname and lastname and it can generate upto 2500 random names.

The application is built with PHP and you only need an apache server to run the application.
# Server Requirements

- PHP >= 5.1

# Below is the code

//PHP array containing lastnames.
$surnames = array(
    'ADEKUNLE',
	'ADEBAYO',
	'AIYELAYIN',
	'AFOLAYAN',
	'ADERIBIGBE',
	'BABALOLA',
	'AYODELE',
	'NINIOLA',
	'OMOLOLA',
	'OLUSUNLE',
	'AJIBOLA',
	'KOLAWOLE',
	'OGENAGPOBO',
	'ADEYEMI',
	'CHIBUEZE',
	'UCHECHUKU',
	'ADEOLA',
	'SISOCHUKU',
	'EYITAYO',
	'ERIOLUWAPE',
	'CHIMRERENKA',
	'ZIMUZO',
	'KAMBILI',
	'NKWACHI',
	'UJECHUKU',
	'OLAMILEKAN',
	'OLUFEMI',
	'OLUWADARASI',
	'ABDULGAFFAR',
	'ABDULLAHI',
	'MUHAMMAD',
	'ABDULJABAR',
	'ABDULSOMOD',
	'OGUNJINRIN',
	'ABUBAKR',
	'AYODELE',
	'ONAOLAPO',
	'AHMAD',
	'ASONIBARE',
	'AMIR',
	'IDOWU',
	'FARUQ',
	'ABIOLA',
	'ADEBOWALE',
	'EMMANUEL',
	'ADENIYI',
	'CHIBUEZE',
	'EYITAYO',
	'CHIBUZOR',
	'ADEBAYO'
);

//PHP array containing firstnames.
$names = array(
    'MARY',
	'EYITAYO',
	'FUNMI',
	'FAITH',
	'DANIEL',
	'ADEOLA',
	'PELUMI',
	'EMMANUEL',
	'KELVIN',
	'GIFT',
	'DEBORAH',
	'FOLASHADE',
	'RICHARD',
	'DANIEL',
	'WILLIAMS',
	'UDOZI',
	'BABALOLA',
	'ANOZIE',
	'DAYO',
	'WALE',
	'RAPHEAL',
	'EWELIKE',
	'HALUCHI',
	'UZE',
	'NACHIKAMDI',
	'RACHEAL',
	'OBINNA',
	'DARA',
	'FATHIA',
	'SODIQ',
	'ALLI',
	'ZAKARIYAH',
	'ADAM',
	'TOLU',
	'YUNUS',
	'LUKMAN',
	'ABDULBASIR',
	'AMINU',
	'MERCY',
	'BILAL',
	'STEPHEN',
	'DANJUMA',
	'HASSAN',
	'HABIB',
	'AMADI',
	'PRAISE',
	'ANOZIE',
	'TADE',
	'UCHE',
	'SAMUEL',
);

	//Generate a random firtsname.
	$random_name = $names[mt_rand(0, sizeof($names) - 1)];

	//Generate a random lastname.
	$random_surname = $surnames[mt_rand(0, sizeof($surnames) - 1)];

	//Combine them together and print out the result.
	echo $random_name . ' ' . $random_surname;

# End of the Program

If you have any challenges feel free to contact me on
+2348133372368 or samprog4u@gmail.com

Thank you
