# To Do List

![hero](https://res.cloudinary.com/ichtrojan/image/upload/v1574958373/Screenshot_2019-11-28_at_17.22.25_gyegdr.png)

## Introduction

A simple todolist application written in Go 

## Requirements
* MySQL installed
* Go installed

## Installation

* Clone this repo 

```bash
git clone https://github.com/rohanxminocha/to-do-list
```

* Change Directory

```bash
cd go-todo
```

* Initiate `.env` file

```bash
cp .env.example .env
```

* Modify `.env` file with your correct database credentials and desired Port

## Usage

To run this application, execute:

```bash
go run main.go
```

You should be able to access this application at `http://127.0.0.1:4040`

>**NOTE**<br>
>If you modified the port in the `.env` file, you should access the application for the port you set
