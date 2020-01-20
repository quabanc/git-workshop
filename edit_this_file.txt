class HelloWorld
  def initialize(name)
    @name = name.capitalize
  end
  # working here
  def say_hi
    puts "Hello #{@name}!"
  end

  # TODO: Remove this comment and the method below.
  def say_bye
    puts "Good-bye #{@name}!"
  end
end
