# OpenCart 3.x Virtual POS Integration

You can report your errors under this heading http://www.karesoft.com.tr/opencart-3-x-sanalpos-entegrationu-ucFree.

If the table that should be in the database does not come in normal setup, you can read it from phpmyadm. Let's pay attention to the Table Prefix part "oc_"
``
CREATE TABLE IF NOT EXISTS `oc_webposbank` (
`bank_id` INT (11) NOT NULL AUTO_INCREMENT,
`name` varchar (64) NOT NULL,
`image` varchar (64) NOT NULL,
`method` varchar (64) NOT NULL,
`model` varchar (64) NOT NULL,
`short` varchar (64) NOT NULL,
`status` tinyint (1) NOT NULL,
PRIMARY KEY (`bank_id`)
) ENGINE = MyISAM DEFAULT COLLATE = utf8_general_ci;
``

# Integrated Banks:
Warranty
Construction loans
EST (FinansBank, HalkBank, İş Bank, AkBank)
KuwaitTurk
Payu
I-Money
# Information
Author: Agit ISIK
E-mail: agit@karesoft.com.tr
Web: www.karesoft.com.tr 
