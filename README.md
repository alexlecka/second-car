# second-car
Project about gathering information from the internet about second hand used cars and comparing them by different features across countries.

Current state (as of 9th Jan 2024):\n
    I have managed to write a script to collect data about all Opel cars on the martkplaats.nl website. For now, I collect the ad title, the link on the website, the year of construction of the car, fuel type of the car, transmission type of the car, vehicle type (?), mileage in km. 

    Issues: There seems to be an issue some hyper-references - the elements lack a connection to their link so it's not possible to trace back the ad. I don't think this is very solvable. Some cars are missing mileage information - not something I can do anything about. 

    Next to do's: 1. Add car model information
                  2. Find some car classification based on the parameters I have available. (car size, ideally car class, value new could be a good one, etc.)
