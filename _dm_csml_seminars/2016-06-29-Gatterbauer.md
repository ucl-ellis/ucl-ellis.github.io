---
layout: dm_csml_seminar_event
posted_date: 2020-03-01
event_start_time: 2016-06-29 13:00
event_end_time: 2016-06-29 14:00
img: ellis-logo.png
alt: image-alt
join_link: Roberts G08 Sir David Davies LT (TBC)
location: Zoom
speaker: Wolfgang Gatterbauer
affiliation: CMU
title: Approximate lifted inference with probabilistic databases
summary: <p>ABSTRACT&#58;<br/>Performing inference over large uncertain data sets is becoming a central data management problem. Recent large knowledge bases, such as Yago, Nell or DeepDive, have millions to billions of uncertain tuples. Because general reasoning under uncertainty is highly intractable, many state-of-the-art systems today perform approximate inference by reverting to sampling. This talk shows an alternative approach that allows ranking answers to hard probabilistic queries in guaranteed polynomial time, and by using only basic operators of existing database management systems (i.e. no sampling required).<br/>(1) The first part of this talk develops upper and lower bounds for the probability of Boolean functions by treating multiple occurrences of variables as independent and assigning them new individual probabilities. We call this approach dissociation and give an exact characterization of optimal oblivious bounds, i.e. when the new probabilities are chosen independent of the probabilities of all other variables. Our new bounds shed light on the connection between previous relaxation-based and model-based approximations and unify them as concrete choices in a larger design space.<br/>(2) The second part then draws the connection to lifted inference and shows how the problem of approximate probabilistic inference can be entirely reduced to a standard query evaluation problem with aggregates. There are no iterations and no exponential blow-ups. All benefits of relational engines (such as cost-based optimizations, multi-core query processing, shared-nothing parallelization) are directly available to queries over probabilistic databases. To achieve this, we compute approximate rather than exact probabilities, with a one-sided guarantee&#58; The probabilities are guaranteed to be upper bounds to the true probabilities, which we show is sufficient to rank the top query answers with high precision. We give experimental evidence on synthetic TPC-H data that this approach can be orders of magnitude faster and also more accurate than sampling-based approaches.<br/>(Talk based on joint work with Dan Suciu from TODS 2014 and VLDB 2015&#58; http&#58;//arxiv.org/pdf/1409.6052, http&#58;//arxiv.org/pdf/1412.1069)<br/></p>
icalendar: /ics/id/295
calendar_name: csml_id_295.ics
old_url: http://www.csml.ucl.ac.uk/events/295
---
