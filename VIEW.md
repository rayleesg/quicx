## Default view structure
```php
<?php
$classes = classNames( "qx-element qx-element-{$type} {$field['class']}");
?>

<div id="<?php echo $id; ?>" class="<?php echo $classes ?>">
  <!-- content -->
</div>
```

## How to add assets
```php
<?php
$document = JFactory::getDocument();
$template = JFactory::getApplication()->getTemplate();
$document->addScript("templates/".$template."/quicx/elements/animatednumber/assets/js/jquery.countTo.js");
$document->addStyleSheet("templates/".$template."/quicx/elements/animatednumber/assets/js/animatednumber.css");
?>
```
