Test-Task
=========

Test Task for PHP developer
<html>
  <head>
    <title></title>
  </head>
  <body>
    <p>
      <?php
        class Animal 
        {
            function __construct ($name)
            {
                $this->name = $name;
            }
        }
        class Cat extends Animal
        {
            public function meow()
            {
                return "Cat $this->name is saying meow.";
            }
        }
        $cat = new Cat('Garfield');
        echo $cat->meow();
      ?>
      </p>
  </body>
</html>
