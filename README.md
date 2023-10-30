ML Engineer Assignment

The context

In order to reach the next phase of the recruitment process, what’s a better way to start than letting your skills do the talking? Time for some data processing. 😉

For the purpose of the interview, we are also interested in the explanations, the reasoning and decision-making together with the actual output.

From a tech stack perspective, you can use any programming language or toolset you're comfortable with. We learn to master new tools every day and we think the reasoning behind decisions is the one that counts the most. You can probably get up to speed with the rest rather quickly.

We're sure you'll kick ass! 💪

The assignment

Create a new model that is able to extract products from Furniture Stores.

Inputs

You’ll be given a list of URLs from furniture stores sites. Most will have products on them, some won’t, some won’t even work at all.

Refer to the Furniture Store Inputs file.

Outputs

We expect a list of product names extracted from every URL, but you can get creative in presenting your results. See what the most popular product is, aggregate all the pages of a site etc.
Try to showcase what your solution is best at.

Guidelines

An approach that usually works well with such extraction problems is to create a NER (Named Entity Recognition) model and train it to find your entities (you have one entity, ‘PRODUCT’).

- In order to create such a model you need training data, you can also extract that from the input pages.
- Crawl ~100 pages from the list above & extract the text from it.
- Find a way to tag some sample products from these texts.
- Train a new model from the examples you just made.
- Use it to extract product names from some new, unseen pages.

We recommend using the Transformer architecture from the sparknlp library or the Huggingface transformers library.

Criteria

There are a lot of ways you can showcase your assignment and prove how great it is, but there is a list of criteria which we believe is mandatory and must be present in any great project:

- Explain your though-process, walk us through how the solution works, what else you tried and why you decided to go this route and not others. These explanations help us know you better and help avoid misunderstandings.
- Make your code clear. This is a PoC at most, so it doesn't need to follow production-level code standards. But here, most PoC's turn into production solutions, so make it robust, concise and easy to extend/collaborate.
- Present your outputs clearly. Show how good your solution is using clear metrics, try to convince us this has the potential to be used for real some day.

📌 Remember: this is just a rough guideline, please feel free to use any tool or solution you wish, especially if you know it will be better or more interesting!

