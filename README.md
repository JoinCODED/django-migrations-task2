# First Task

Follow the steps below and get some hands on practive with django migrations.


## Setup
- Clone the Repository
- run poetry install
- poetry run python manage.py runserver 0.0.0:8000

## Steps
- Run initial migrations
- Create A super user
- Login to the admin and create a Pokemon.
- Create a new model Called MonsterType with one field (name)
- Create your migrations
- Add a new foreignkey field (monster_type) to the MonsterType model with a default value of 1.
- Try to make and apply your migrations. This should fail.
- Manually create your next migration so that it creates a MonsterType object.
- Run your migration
- Try to make and apply your migrations. This should succeed. 
- Create a new model called Trainer and add a foreignKey from Trainer to Pokemon with no default value (Do not makemigrations yet!).
    - Before you run your migration, change the next line to represent your guess (type YES infront of the one you think is correct)
        - I will need to provide a default value
        - I will not need to provide a default value
- Run your migrations
    - Where you right?
- Bonus: Create a new model called GYM and add a foreignKey from Trainer to GYM. Your task is to make it so that you only need single new migration file, with a single migrate command.

