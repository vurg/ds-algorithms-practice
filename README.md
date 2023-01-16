# Data Structures and Algorithms - Practice
Hello, this space is for data structures and algorithms practice.

Lambda expression example in Java:
```
List<String> names = Arrays.asList("Alice", "Bob", "Charlie", "David");

Collections.sort(names, (a, b) -> a.compareTo(b));

System.out.println(names);
```
This will print out the list of names in alphabetical order: [Alice, Bob, Charlie, David].

Anonymous function example in Java:
```
List<String> names = Arrays.asList("Alice", "Bob", "Charlie", "David");

Collections.sort(names, new Comparator<String>() {
    @Override
    public int compare(String a, String b) {
        return b.compareTo(a);
    }
});

System.out.println(names);
```
This will print out the list of names in reverse alphabetical order: [David, Charlie, Bob, Alice].
