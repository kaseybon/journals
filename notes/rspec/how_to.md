# How To's

**Install RSpec**

```
gem install rspec
```

**Initialize RSpec for a project**

Inside of the project folder:

```
rspec --init
```

**Describe Block**

Inside of */path/project_spec.rb*:

```
require "spec_helper"
require_relative 'file_your_testing_without_extension'

describe Class do
	# your examples go here
end
```

**Run a Spec**

```
rspec */path/project_spec.rb*
```

**Require a class**

In project file:

```
class Class

	# Classy stuff

end
```


In project_spec.rb:

```
require "spec_helper"
require_relative 'file_your_testing_without_extension'
require Class

describe Class do
	# your examples go here
end
```