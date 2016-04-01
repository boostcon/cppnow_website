---
layout: default
permalink: /individual_sponsors/
---

<style>
    img[alt=Donate]
    {
        float:center;
    }

    img[alt="Boost C++ Libraries"]
    {
        float:center;
    }

    div.sponsor_name
    {
        text-align: center;
    }

    div.level_name
    {
        text-align: center;
    }

    div.sponsor_name
    {
        text-align: center;
    }

</style>


{% for category in site.data[site.current_year].sponsors.individual_sponsors.categories %}

###<div class="level_name">{{ category.title }}</div>
    
{% for sponsor in category.sponsors %}
<div class="sponsor_name">{{sponsor.name}}</div>
{% endfor %}

{% endfor %}
    


***


C++Now is brought to you by

![Boost C++ Libraries]({{site.baseurl}}/images/boost.png)


You can make a [donation to Boost](http://www.boost.org/donate/) in any amount.


For a copy of the C++Now Corporate Sponsorship Prospectus contact [sponsorship@cppnow.org](mailto:sponsorship@cppnow.org?Subject=C++Now%20Sponsorship).



***


For individuals, C++Now offers the **Boost Scholarship Sponsorship**:


The Boost Scholarship Fund supports two programs that directly benefit C++ students and indirectly benefit the entire C++ community.

####Boost Summer of Code
The Boost Scholarship Fund supports Boost Summer of Code. This program is modeled after the Google Summer of Code program, in which Boost is a long time participant. Like GSoC, BSoC projects provide funding for students to work on specific Boost Library projects over the summer. BSoC is designed to supplement the GSoC program by allowing Boost to accept students that would otherwise be rejected by GSoC due to funding or eligibility.

####C++Now Student/Volunteer Program
The Boost Scholarship Fund supports [C++Now's Student/Volunteer Program]({{site.baseurl}}/student_volunteer_program/). Each year, the conference helps a small group of young programmers attend the conference. In exchange, the students help the C++Now staff in running the conference.


Contributions to the Boost Scholarship Fund are earmarked\* to support these programs and can be made in any amount, but specific benefits attach at certain sponsorship levels.

####Boost Scholarship Sponsor – Gold Level:
* $500 tax deductible contribution**
* Recognition on Boost and C++Now websites as "Boost Scholarship Sponsor – Gold Level"
* Boost Scholarship Sponsor tee shirt 
* Recognition at C++Now Welcome and Closing sessions 
* Invitation to Meet The Student/Volunteers Breakfast at C++Now

####Boost Scholarship Sponsor – Silver Level:
* $250 tax deductible contribution**
* Recognized on Boost and C++Now websites as Boost Scholarship Sponsor – Silver Level" 
* Boost Scholarship Sponsor tee shirt

####Boost Scholarship Sponsor – Bronze Level:
* $125 tax deductible contribution**
* Recognition on Boost and C++Now websites as "Boost Scholarship Sponsor – Bronze Level"


![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)


Every donation comes with the knowledge that you are making the difference in the career of a C++ student.


If you have any questions about individual sponsorships or any of these programs contact [sponsorship@cppnow.org](mailto:sponsorship@cppnow.org?Subject=C++Now%20Sponsorship).



***


\* It is the intent of the Boost Steering Committee to honor the wishes of all donors; however, an earmark does not represent a legal obligation.

\** Tax deductible amounts are reduced by the fair market value of benefits received.
