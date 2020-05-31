# Github user guide for contributing to data collected about COVID-19.

This user guide is for those who have little or no experience using `git` or` github` especially in a context project distributed with a large number of contributors.

- Create a branch off the master branch of the data file (https://github.com/MounaBelaid/covid19datatunisia/edit/master/dist/data.csv),
you’re making a copy, or snapshot, of master as it was at that point in time.
- Type a branch name, into the new branch text box.
- Select the blue Create branch box or hit “Enter” on your keyboard.

Now you have two branches, master and the branch you have created. They look exactly the same, but not for long! Next we’ll add our changes to the new branch.

On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. 
Commit messages capture the history of your changes, so other contributors can understand what you’ve done and why.

- Click the  pencil icon in the upper right corner of the file view to edit. In the editor, the changes that you would make consist of 
adding rows to the data file (https://github.com/MounaBelaid/covid19datatunisia/edit/master/dist/data.csv) according to what official
sources declare.
The new rows contain data represented respectively in every column as follows :

▲ date - The date in YYYY-MM-DD form.

▲ location - The name of the government as provided by the data sources.

▲ location_type - The type of location using the covid19R controlled vocabulary. In this case, it's “state”.

▲ location_code - A standardized location code using a national or international standard. In this case, . See https://www.iso.org/obp/ui/#iso:code:3166:TN for details.

▲ location_code_type The type of standardized location code being used according to the covid19R controlled vocabulary. Here we use “ISO 3166-2”.

▲ data_type - the type of data in that given row. Includes cases new : new confirmed Covid-19 cases during on the current date,
recovered_new : new number of patients recovered on the current date and deaths_new : new deaths on the current date.

▲ value - number of cases of each data type.

- Write  commit message that describes your changes.
- Click Commit changes button.
- Now that you have changes in a branch off of master, you can open a pull request. When you open a pull request,
you’re proposing your changes and requesting that someone review and pull in your contribution on data and merge them into their branch.
