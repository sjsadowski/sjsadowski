~/.plan
=======

| Writing                      | Development                 |
|------------------------------|-----------------------------|
|- Managing Technical Debt     |- Personal site redevelopment|
|- Breaking Down Microservices |- Web contactware            |

```py
#shamelessly stolen from Adam Hopkins (@ahopkins)
class Stephen(Person):

  def __init__(self):
    self.work = [
      UturnData(role=["VP ProServ", "DevOps & Modernization Practice Lead"]),
      MetaMeta(role=["Founder & CEO"]),
      DigitalForHer(role=["Managing Partner, Technology"])]
    self.oss = Sanic(role=["Steering Council","Core Developer","Release Manager"])
    self.home = [UnitedStates("Chicago"), UnitedStates("Dallas")]
    self.hobbies = ["Cooking","Coffee","Reading","Dining","Travel"]
    self.education = ["MBA, IT Management"]
   
  async def run(self, inputs: Coffee) -> None:
    while True:
      await self.work.do(inputs)
      await self.education.do(inputs)
      await self.oss.do(inputs)
      await self.hobbies.do(inputs)
  
  def quit(self):
    raise NotImplementedError


```
