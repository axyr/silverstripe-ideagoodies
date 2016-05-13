# silverstripe-ideagoodies
Livetemplates and more for the Silverstripe framework

## live templates

@see https://www.jetbrains.com/help/phpstorm/2016.1/sharing-live-templates.html

### db [tab]
```
/**
 * @var array
 */
private static $db = [
    '$NAME$'    => '$END$'
];
```

### ho [tab]
```
/**
 * @var array
 */
 private static $has_one = [
    '$NAME$'    => '$END$'
];
```

### hm [tab]
```
/**
 * @var array
 */
 private static $has_many = [
    '$NAME$'    => '$END$'
];
```

### mm [tab]
```
/**
 * @var array
 */
 private static $many_many = [
    '$NAME$'    => '$END$'
];
```

### fieldLabels [tab]
```
/**
 * @param bool $includerelations
 * @return array
 */
public function fieldLabels($includerelations = true)
{
    $labels = parent::fieldLabels($includerelations);

    $END$
    
    return $labels;
}
```

### getcms [tab]
```
public function getCMSFields()
{
    $fields = parent::getCMSFields();
    
    $END$
    
    return $fields;
}    
```
