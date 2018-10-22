* It's better to read a file line by line and than reading it all at once into memory as it
consumes a lot of OS memory for larger files especially in a production environment.
More reading in this [SO answer](https://stackoverflow.com/a/5546681/272398)
Source: Ended up discovering this when working on a Ruby task that required me to read from a file