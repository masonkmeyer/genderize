[![Go Report](https://goreportcard.com/badge/github.com/masonkmeyer/genderize)](https://goreportcard.com/badge/github.com/masonkmeyer/genderize)
![Build](https://github.com/masonkmeyer/genderize/actions/workflows/build.yml/badge.svg)

# Genderize

Genderize is a go client for the [genderize.io](https://genderize.io/) API.


 ## Examples

 You can use this library to call the API client. 
 
 ```golang
client := genderize.NewClient()
prediction, rateLimit, err := client.Predict("michael")
 ```

This client also supports batch predictions.
