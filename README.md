# jsonforgo
json for go coures on stepik

Положить файл в папку с проектом и добавить в main:

	file,_:= os.Open("./json")
	data, err := ioutil.ReadAll(file)
	if err != nil {
		// ...
	}
  // ...
