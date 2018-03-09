## Questions

1. What is the difference between `new` and `create` for a model?
create calls upon new in order to really make the thing and save it; new makes a blank version of it and doesn't save; new + save is the same as create

2. What command followed after with `Cat.new` will emulate the same behavior as `Cat.create`?
save

3. What is the default integer column that exists on every table but we did NOT define?
nil

4. What single line of ruby code can insert a cat with the name "Kira" in the database?
cat = Cat.create(name: "kira")

5. How did you like this homework in comparison with the previous homeworks?
this was really overwhelming at first... i really wish i had more guidance as to where to create files sometimes, since it always takes me a while each time i do the assignments to get uesd to the folders again
but i liked being able to make the things and see the output on the home page - i could make sure i was really understanding the difference between new/create and was sorta getting this stuff more than the other homeworks.
also making it cats is nicer than just students/teachers. :)

(also the spec was wrong, it said the field for a booleach check box is f.checkbox, but it's f.check_box)