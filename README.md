# Spark simple exmaples ver 0.1.0

This is a set of Spark application script examples,
which run on spark-shell.

You can use these scripts as references and execute them on spark-shell with :load function as a test.

feature

* Easy to run
* Easy to modify
* Suitable for beginners

THe following is the example to execute on spark-shell by :load function.
If you want to know the detail of this scrpits,
please refer to "src" directory.

## WordCount
Start spark-shell

```shell
$ spark-shell
```

Load scala scripts

```
scala> :load src/WordCount.scala
```

## Cache usage

Start spark-shell

```shell
$ spark-shell
```

Load scala scripts

```
scala> :load src/CacheUse.scala
```

## SQL usage

Start spark-shell

```
$ ./bin/shell_csv.sh
```

Load scala scripts

```
scala> :load src/SqlUsage.scala
```

## KMeans

Start spark-shell

```
$ ./bin/shell_csv.sh
```
Load scala scripts

```
scala> :load src/KMeans.scala
```

## KMeans with large data

Start spark-shell

```
$ ./bin/shell_large_kmeans.sh
```

Load scala scripts

```
scala> :load src/KMeansLarge.scala
```

## Tweet printing

Create config.properties

```
twitter_consumerKey=xxxxxxxxx
twitter_consumerSecret=xxxxxxxxx
twitter_accessToken=xxxxxxxxx
twitter_accessTokenSecret=xxxxxxxxxxxx
```

Start spark-shell

```
$ ./bin/shell_tweet.sh
```

Load scala scripts

```
scala> :load src/Tweet.scala
```

# Release note

* 0.1.0: first version with several simple examples.
