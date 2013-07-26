UKPhoneValidator
================

UKPhoneValidator is an extension for validation of United Kingdom phone numbers in all possible ways. 

Requirements

Yii 1.0 or above

Usage

The following model code validates attribute in UKPhoneValidator:

~~~
[php]
public function rules()
{
   return array(
      array('phone', 'application.extensions.UKPhoneValidator')
           );
}

~~~
Also allowEmpty can be set and message for empty entry.
