## R-Programming-Assignment2

## A pair of functions that cache the inverse of matrix 

## Caching the inverse of a matrix by creating  a special matrix object

 makeCacheMatrix <-function (m= matrix()) {

## Initialising the Inverse Property

  i<- NULL

## Method to set the matrix

 set<- function(matrix)
  {
    m<<- matrix
     i<<- NULL
  }

## Method to get the matrix
    get <- function() {
## Return the matrix
    m
 }
 
## Method to set the inverse of the matrix
  setInverse <- function(inverse) {
  i <<- inverse
}

## Method to get the inverse of the matrix
    getInverse <- function() {
## Return the inverse property
    i  }

