bootforms-php
=============

Framework Independant Bootstrap 3 Form Generator

#USE

    use kilrizzy\BootformsPHP\Bootform;
    $form = new Bootform();
    echo $form->field(array(
	    'label' => 'First Name',
	    'type' => 'text'
    ));

#TTD

- Fix errors popping up
- Convert to BS3
- Find + Add any missing form fields
