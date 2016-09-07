We Can Splat if we Want to
==========================

Track: Weird Ruby

Audience: Beginner/Intermediate


Abstract (public, 600 characters)
--------

Ruby is a language we all love. It has an elegance and aesthetic
that is rivaled by few. The more we learn about the language the
deeper our love becomes. Some areas of Ruby are underutilized
outside of the very seasoned. Learning one of these corners can
open up a whole new world of ideas. Let's dive into one corner and
learn how we can utilize some basic pattern matching like that found
in other languages. You just might change some of your current code.

Details (outlines, outcomes, intended audience, etc.)
-------

I would like beginner and intermediate developers to gain an
appreciation for splat and double splat operators and start thinking
of uses of implicit and explicit conversions and how to utilize them.

I'll start with the basics of the splat operator used in assignments,
blocks, and arguments. Most beginners know to use the splat at the
end of an argument list as a variable argument list so we will start
there. Then I will show the different positions within the argument list
where splat can be used for a simplified pattern matching.

We will then continue on to splatting out an array into
arguments to show that we can go both ways. Part of showing the usage
of splat in arguments we will implement `car` and `cdr` as well as the
infinite expansion of those just like lisp (`ex. cadr, caaddar, etc.`).

After a few examples of arguments I will show that it is the same
as an assignment statement using a splat on the left hand side.

Moving to the right hand side of the assignment operator splat we
will start to learn about implicit vs explicit conversion. I will
show both `to_a` and `to_ary` on the same object. I will expand this
explanation to the double splat to include `to_h` and `to_hash`.
We will then see what the difference are in there implicit vs
explicit use cases.

Now that the audience is thinking about implicit vs explicit conversions
I plan to show a complete list of Ruby's methods for doing this as
well as quick example uses.

I hope that this introduction will encourage the use and exploration
of conversions in order to maximize the usefulness of objects with
less code.

Pitch (why this talk, why me?)
-----

Splat is a Ruby operator that is underutilized and simple to understand.
I believe this a good place to start to step past the beauty of
Enumerable and really appreciate the language. Using splat touches
on implicit and explicit conversion that can be introduced to the
less seasoned rubyists. In the recent past there has been a big push
towards functional styles and languages that support pattern matching
and although it doesn't get us all the way there the splat does lead us
to some poor person's pattern matching. I believe that learning this
simple and elegant operator opens up a new world of possibilities for
playing and growing.

I've been writing Ruby since 2005 and Rails since 2006. I took over
the local Ruby group in 2011 so I could give more to the community.

I love Ruby because of its power and elegance, but as a consultant I
often find a lack of the beauty in simplicity being underutilized and
unknown. I want to start to help people grow in understanding the
advantages that Ruby has to offer.

I've done some research on conversions and on splat itself. There are
some good articles out there, but I'm surprised that there is not an
emphasis on how this can lead to more intention revealing code that
isn't muddled up in the details.

I've spoken many times at local user groups and it leads to many people
asking for help or thanking me later. I want to bring these lessons to a
wider audience and become more involved in the community that has given
me so much.

Bio
---

Amos is a freelance consultant under the name Binary Noggin. He joins
teams as a developer to help improve process and technical skills. He
is a host on the [This Agile Life](http://thisagilelife.com) where he
can be heard talking about process, code, and trust.

Amos started using Ruby in 2005 just to be different than his coworker.
He found the language and community both warm and inviting.

When Amos isn't coding he loves hanging out with his five children,
playing ukulele, making beer, and roasting coffee.
