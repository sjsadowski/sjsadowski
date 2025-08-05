~/.plan
=======

| Writing                      | Development                 |
|------------------------------|-----------------------------|
|- Managing Technical Debt     |- clyx|events                |
|- DevOps in an AI world       |- pWebServer                 |

```py
#shamelessly stolen from Adam Hopkins (@ahopkins)
class Stephen(Person):

  def __init__(self):
    self.work = [
      MetaMeta(role=["Founder & CEO"]),
      ClyxLLC(role=["Founder & Chief Architect"]),
      DigitalForHer(role=["Managing Partner, Technology"]),
      PeerData(role=["Head of Technology Strategy & Integration"])]
    self.oss = Sanic(role=["Steering Council","Core Developer","Release Manager"])
    self.home = [UnitedStates("Chicago"), UnitedStates("Dallas")]
    self.hobbies = ["Cooking","Coffee","Reading","Dining","Cigars","Dogs"]
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
