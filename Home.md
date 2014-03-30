# Welcome

Welcome to Atlantis X PHP Framework Project Page. 

## Framework Key Features


## Quickstart

```
$ git clone https://nematix@bitbucket.org/nematix/atlantis.git
```

## Naming Convention

### Identification

System suggesting a standard naming convention to be used for identification on variable, database columns and others. Identification naming convention specification example for identification card as follow.

```
idic <id><name>
```

Identification naming is in two part, first is reserve name <id> and second part is name of the identification and it can be any name. In example is `ic` refer to identification card.

```
idic_no <id><name>_<meta>
```

Third part of the naming convention is to describe a sub information of the identification, it can be a actual number of the identification itself, a description or any meta data that can be attached to the identification. In example `no` refer to actual number of the identification.

```
$idic = 1
$idic_no = 'A123456'
$idic_text = 'Identification Card'
```

Example showed a basic usage of the naming convention in source code. The `$idic` variable might refer to auto-increased id in database configuration and `$idic_no` might refer to actual identification number.

## Application (Atlantis\Application)

### Details
Details is representation of data or data structure of the application. Details format is a JSON structure work as reference for application to save to get data related to current application.

### Cards
Cards is a collection of form element in to presenting data from Details.

### Forms
Forms is a HTML elements.