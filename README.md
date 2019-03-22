# Ecology 101

Hi, in this class we're going to cover:

- bulleted
- lists

and there will be plenty of code snippets:

```
class SkeletonAgent(BaseAgent):

    """Base class inheriting from BaseAgent that manages data provided by the rlbot framework,
    and converts it into our internal data structure, and extracts further useful info."""

    def __init__(self, name: str = 'skeleton', team: int = 0, index: int = 0):

        super(SkeletonAgent, self).__init__(name, team, index)
        self.game_data = GameData(name, team, index)
        self.controls = SimpleControllerState()

    def initialize_agent(self):
        self.game_data.read_field_info(self.get_field_info())
```


Here's the rest of the course content:

[Week 1: Animals](week1.md)

[Week 2: these all actually just link to week 1](week1.md)

[Week 3: these all actually just link to week 1](week1.md)

[Week 4: these all actually just link to week 1](week1.md)

[Week 5: these all actually just link to week 1](week1.md)

[Week 6: these all actually just link to week 1](week1.md)
