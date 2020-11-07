# attribmanager

##### A simple pythonic module to lock and hide class attributes


## Installation

`pip install attribmanager`

## Usage

```
import attribmanger

class example(attribmanger.manage):

	def __init__(self):

		self.mylist = ["item 1", "item2"]
		self.lock("mylist")
		# mylist is read only and cannot be edited now
```