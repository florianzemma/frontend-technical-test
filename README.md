# Context :

At leboncoin, our users can share messages about a transaction, or ask for informations about any products.

Your job is to create the interface to consult those messages.
The interface needs to work on both desktop & mobile devices.

In addition to your code, a README explaining your thought process and your choices would be appreciated.

# Explanation :

Time : approximately 5h I think 

Hi, 

For this test I've choosen to use Tailwind css for styling, because I think it's cool, tailwind is easy to understand, customizable,
provides good features for responsive and I think I'am more productiv with.
To fetch data i've used axios because I think axios provide more features and is better for typing with typescript than fetch api.

I've used React Context API to share the userId between components / pages, because if the tree grow we will can access the userId i think it can be useful in the future of the application.
I've make an Layout component that accept children as props, so the header and the footer can be displayed in all the application.

I've started to create the conversation page where I display the list of conversations with a List-component inside this component there is a card component that display de conversations informations,
this list component his memoized to avoid unwanted re-renders when his props doesn't change.

The next page that display chat contains one input component , and one message list with bubble component to display messages

I've made the bonus1 you can create new conversations for a user, i've not respected exactly the swagger for this root because it was not corresponding with the already created data,
so I've added some keys on the sended object of the POST request to match more the data provided.

There is some error messages on the constants file, I've hesitated to put this messages on ENV to change them without redeploying, just by restarting the container,
but at the moment there are  in the constants files.

I've tried to make something beautifuler than the sketches you provided, I hope you will appreciate it

See you,
Florian.


