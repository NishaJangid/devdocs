---
group: functional-testing-framework-guide
title: Functional Testing Framework Entities
---
Functional Testing Framework entities enable you to create and modify functional tests. 
For example, you want to cover with functional tests the process of creation the {% glossarytooltip f0dcf847-ce21-4b88-8b45-83e1cbf08100 %}widget{% endglossarytooltip %} {% glossarytooltip 8d40d668-4996-4856-9f81-b1386cf4b14f %}Catalog{% endglossarytooltip %} {% glossarytooltip 50e49338-1e6c-4473-8527-9e401d67ea2b %}Category{% endglossarytooltip %} Link.
To do this you have to create [injectable test]({{ page.baseurl }}/mtf/mtf_entities/mtf_testcase.html). As widget functionality is not covered with tests, you need to create widget [fixture]({{ page.baseurl }}/mtf/mtf_entities/mtf_fixture.html), that is your object for testing. You will describe the test data that will be applied to the widget object in [repository topic]({{ page.baseurl }}/mtf/mtf_entities/mtf_fixture-repo.html). You want to automate creating of Catalog Category Link widget, that requires to have a category. As far creating of new category is out of the scope of your testing, you will use [handlers]({{ page.baseurl }}/mtf/mtf_entities/mtf_handler.html) to prepare it. To understand what blocks and pages you need in the test, you should perform tests manually. Using [blocks]({{ page.baseurl }}/mtf/mtf_entities/mtf_block.html) and [pages]({{ page.baseurl }}/mtf/mtf_entities/mtf_page.html) entities you can create and define blocks and pages objects for tests. When you have all building blocks forthe test you can determine steps of [injectable test]({{ page.baseurl }}/mtf/mtf_entities/mtf_testcase.html). Any test requires different variations of [data sets]({{ page.baseurl }}/mtf/mtf_entities/mtf_dataset.html) and corresponding [constraints]({{ page.baseurl }}/mtf/mtf_entities/mtf_constraint.html). 

Following is a list of all FTF entities.

- [Fixture]({{ page.baseurl }}/mtf/mtf_entities/mtf_fixture.html)
  - [Fixture overview]({{ page.baseurl }}/mtf/mtf_entities/mtf_fixture.html)
  - [Create new fixture]({{ page.baseurl }}/mtf/mtf_entities/mtf_fixture.html#mtf_fixture_create)
  - [Read and update new fixture]({{ page.baseurl }}/mtf/mtf_entities/mtf_fixture.html#mtf_fixture_read)
  - [Add repository to the fixture field]({{ page.baseurl }}/mtf/mtf_entities/mtf_fixture.html#mtf_fixture_repositoy)
  - [Add data source to the fixture field]({{ page.baseurl }}/mtf/mtf_entities/mtf_fixture.html#mtf_fixture_source)
  - [Merge fixtures]({{ page.baseurl }}/mtf/mtf_entities/mtf_fixture.html#mtf_fixture_merge)
  - [Extend fixture]({{ page.baseurl }}/mtf/mtf_entities/mtf_fixture.html#mtf_fixture_extend)
  
  
- [Fixture Repository]({{ page.baseurl }}/mtf/mtf_entities/mtf_fixture-repo.html)

- [Handler]({{ page.baseurl }}/mtf/mtf_entities/mtf_handler.html)

- [Block]({{ page.baseurl }}/mtf/mtf_entities/mtf_block.html)

- [Typified element]({{ page.baseurl }}/mtf/mtf_entities/mtf_typified-element.html)

- [Page]({{ page.baseurl }}/mtf/mtf_entities/mtf_page.html)

- [Constraint]({{ page.baseurl }}/mtf/mtf_entities/mtf_constraint.html)

- [Data set]({{ page.baseurl }}/mtf/mtf_entities/mtf_dataset.html)

- [Test case]({{ page.baseurl }}/mtf/mtf_entities/mtf_testcase.html)

- [Scenario test]({{ page.baseurl }}/mtf/mtf_entities/mtf_scenariotest.html)


