# cs20006-assignment--4-solved
**TO GET THIS SOLUTION VISIT:** [CS20006 Assignment- 4 Solved](https://www.ankitcodinghub.com/product/cs20006-assignment-4-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;92974&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS20006 Assignment- 4 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
<div class="page" title="Page 1">
<div class="layoutArea">
<div class="column">
&nbsp;

</div>
</div>
<div class="layoutArea">
<div class="column">
We need to develop a rudimentary railway reservation / booking system (somewhat like IRCTC Train Ticket Booking, but extremely scaled down in features). We present various stages of this development process leading finally to the specific tasks of the assignment.

1 Specification

This is the outline specification that has been acquired from the client.

1.1 Requirement Statement

The entities involved in the booking system design include:

<ul>
<li>Station (Section 1.4.1): Every Station is identified by its name. Booking is done between any two Stations.</li>
<li>Railways: It is the Indian railways. It has a collection of Stations with pairwise distance between Stations known a priori. Naturally, there can be only one Railways, called IndianRailways, in the system.</li>
<li>*Date: Any valid date in dd/MMM/yyyy or dd/mm/yyyy format1 is allowed. No same day booking is allowed. Hence the date of travel must be later than the date of booking (current date in the system). Booking for up to one year in advance is allowed.</li>
<li>BookingClass (Section 1.4.2): There are several BookingClasses for travel (as in Indian Railways fare classes explained). Each BookingClass has the following attributes:– Name: Name of the BookingClass

1Choice may be made between the two formats – both need not be supported</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
1

</div>
</div>
</div>
<div class="page" title="Page 2">
<div class="layoutArea">
<div class="column">
<ul>
<li>– &nbsp;Fare Load Factor: The factor by which the fare for travel by this BookingClass would be loaded over the base fare. This may change from time to time.</li>
<li>– &nbsp;Seat / Berth: Whether the BookingClass provides sleeping berths or just seats. This will not change in future.</li>
<li>– &nbsp;AC / Non-AC: Whether BookingClass is air-conditioned or otherwise. This will not change in future.</li>
<li>– &nbsp;# of Tiers: How many tiers exist in the coach for this BookingClass. This will not change in future.</li>
<li>– &nbsp;Luxury / Ordinary: Whether this BookingClass is considered luxurious by the Government. This may change from time to time.</li>
<li>– &nbsp;*Reservation Charge: The reservation or booking charge as levied for the BookingClass. This may change from time to time.Further, some BookingCategorys allow for priority booking (called Tatkal2) on a higher Tatkal fare de- pending on the BookingClass of travel and fare as given in the Talkal Charges Matrix in Section 1.4.3.
New booking classes may be added in future.

• *BookingCategory (Section 1.4.3): There are several BookingCategory for travel (as in IRCTC Book

Ticket). Each BookingCategory has the following attributes:

<ul>
<li>– &nbsp;Name: Name of the BookingCategory</li>
<li>– &nbsp;Eligibility: Eligibility criteria / conditions for the BookingCategory – typically dependent on the PassengerFurther,</li>
</ul>
<ul>
<li>– &nbsp;Some BookingCategorys allow for Concessional fare based on the BookingClass and the eligibility of the Passenger as given in the Booking Category Matrix and the Disability Concession Factor Matrix in Section 1.4.3.</li>
<li>– &nbsp;Some BookingCategorys allow for priority (Tatkal) booking on a higher Tatkal fare depending on the BookingClass of travel and fare as given in the Talkal Charges Matrix in Section 1.4.3.New booking categories may be added in future.

• Booking (Section 1.3): A Booking is requested with the following information:</li>
</ul>
<ul>
<li>– &nbsp;fromStation: Station from which the travel starts for the Booking. This is given by the name of the Station</li>
<li>– &nbsp;toStation: Station at which the travel ends for the Booking. This is given by the name of the Station</li>
<li>– &nbsp;*dateOfBooking: Date of travel for the Booking. This must be greater than dateOfReservation andwithin one year of it.</li>
<li>– &nbsp;*bookingClass: BookingClass for the Booking. This is given from a set of available options (as if a drop-down menu, if the application were build with a GUI).</li>
<li>– &nbsp;*bookingCategory: BookingCategory for the Booking. This is given from a set of available options (as if a drop-down menu, if the application were build with a GUI).</li>
<li>– &nbsp;passenger: Details of the passenger including name, date of birth, gender, aadhaar number, mobile number, and disability id. category of the passenger. This is for future extension and optional for now.</li>
<li>– &nbsp;*dateOfReservation: Date on which the Booking is done.On request of a Booking, the same is processed and fare is computed based on the business logic given in Section 1.3. The Booking is then confirmed with PNR and other details on the output. PNR is serially allocated starting with 1.
• Passenger: A Passenger may have the following details:

– name: Name of the passenger comprising (input as three separate strings): ∗ *firstName: Optional if lastName is present

∗ *middleName: Optional

2Tatkal means immediately. It is a ticket issued by the Indian Railways to provide reservation to passengers who have to undertake a train journey at short notice
</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2

</div>
</div>
</div>
<div class="page" title="Page 3">
<div class="layoutArea">
<div class="column">
∗ *lastName: Optional if firstName is present

<ul>
<li>– &nbsp;dateOfBirth: Date of birth to be used for verification of age and decisions about eligibility for aBookingCategory</li>
<li>– &nbsp;gender: Gender of the passenger: male or female – to be used for verification of identity and decisions about eligibility for a BookingCategory</li>
<li>– &nbsp;aadhaar #: 12-digit Aadhaar Number to be used as a unique ID and input as a string</li>
<li>– &nbsp;mobile #: 10-digit Mobile number (optional) and input as a string</li>
<li>– &nbsp;*disability type: Type of disability (optional)</li>
<li>– &nbsp;*disabilityID #: Number of the divyangjan ID (optional) and input as a string. This is used to check eligibility for Divyaang BookingCategory booking.</li>
<li>– &nbsp;category: One of General, Ladies, Senior Citizen, Divyaang, Tatkal, Premium Tatkal1.2 Assumptions
The following assumptions are made for the design:
</li>
</ul>
<ul>
<li>IndianRailways has a given set of Stations with distances known a priori. The list of Stations and distances between them are given as Master Data in Section 1.4. No new station can be added to the IndianRailways and distance between pair of stations do not change.</li>
<li>*A Booking, as requested, is always available, if valid – between any pair of Stations, on any Date, for any BookingClass, in any BookingCategory, and for any Passenger</li>
<li>No passenger information is considered for the Booking</li>
<li>*The booking system would always be in a consistent, well-defined state. All input data (of settable masters like Stations and distance, or Booking inputs etc.), should be validated for format, type, and consistency. All kinds of errors and exceptions in business logic and processing algorithm should also be handled properly.</li>
</ul>
1.3 *Business Logic

The fare between a pair of stations for a booking class is determined through the following steps:

<ul>
<li>Base Fare Rate: The base fare for every KM of travel = Rs. 0.5. This may change from time to time.</li>
<li>Base Fare: The base fare between two stations is computed by multiplying the distance between thestations with the base fare for every KM of travel. The base fare applies to the Sleeper booking class.</li>
<li>Loaded Fare: For booking classes other the Sleeper, the fare is loaded by a factor with respect to the Sleeper booking class fare as shown in the Booking Class Matrix (Section 1.4.2). The load factor may change from time to time.</li>
<li>AC Surcharge: Further, for air-conditioned classes, AC surcharge of Rs. 50 will be charged on the loaded fare. This may change from time to time.</li>
<li>Luxury Tax: Finally, there is a 25% luxury tax to be imposed for all luxury class bookings on the fare computed with surcharge. This may change from time to time. The luxury classification as well as taxation rate may change from time to time.</li>
<li>Depending on the BookingCategory, a passenger may get some percentage of concession on the loaded fare according to the tables given in Section 1.4.3. Currently concessions are allowed in SeniorCitizen and Divayaang categories only. However, in future, concession may be allowed in Ladies category as well.</li>
<li>No concession is allowed for Tatkal booking (in Tatkal and PremiumTatkal categories). For a Tatkal booking, a premium is charged on the base fare (as shown in Section 1.4.3) capped by minimum and maximum amounts and minimum distance of travel. After adding this premium, the loading for the booking class is applied as before (Section 1.4.2).The premium is double of Tatkal for every PremiumTatkal booking.</li>
<li>Finally, a reservation charge is added to the fare depending on the class of travel (Section 1.4.2).</li>
<li>Final fare is rounded to the nearest integer.</li>
<li>dateOfBooking has no effect on the fare.</li>
<li>Passenger has no effect on the fare as it is being ignored for now.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
3

</div>
</div>
</div>
<div class="page" title="Page 4">
<div class="layoutArea">
<div class="column">
1.3.1 Example: Booking Category = General For a booking from Delhi to Mumbai:

By AC3Tier:

<ul>
<li>Distance from Delhi to Mumbai = 1447km</li>
<li>Base fare = 1447km * Rs. 0.5 / km = Rs. 723.50</li>
<li>Loaded fare for AC3Tier = Rs. 723.50 * 2.50 = Rs. 1808.75</li>
<li>After adding the reservation charge, we get Rs. 1808.75 + Rs. (rounded)By ACFirstClass:</li>
</ul>
<ul>
<li>Distance from Delhi to Mumbai = 1447km</li>
<li>Base fare = 1447km * Rs. 0.5 / km = Rs. 723.50</li>
<li>Loaded fare for ACFirstClass = Rs. 723.50 * 6.50 = Rs. 4702.75</li>
<li>After adding the reservation charge, we get Rs. 4702.75 + Rs. (rounded)</li>
</ul>
1.3.2 Example: Booking Category = Senior Citizen For a booking from Delhi to Mumbai:

By AC3Tier for Male:

<ul>
<li>Distance from Delhi to Mumbai = 1447km</li>
<li>Base fare = 1447km * Rs. 0.5 / km = Rs. 723.50</li>
<li>Loaded fare for AC3Tier = Rs. 723.50 * 2.50 = Rs. 1808.75</li>
<li>Concession fare = Rs. 1808.75 * (1.00 – 0.40) = Rs. 1085.25</li>
<li>After adding the reservation charge, we get Rs. 1085.25 + Rs. (rounded)By ACFirstClass for Female:</li>
</ul>
<ul>
<li>Distance from Delhi to Mumbai = 1447km</li>
<li>Base fare = 1447km * Rs. 0.5 / km = Rs. 723.50</li>
<li>Loaded fare for ACFirstClass = Rs. 723.50 * 6.50 = Rs. 4702.75</li>
<li>Concession fare = Rs. 4702.75 * (1.00 – 0.50) = Rs. 2351.375</li>
<li>After adding the reservation charge, we get Rs. 2351.375 + Rs. (rounded)</li>
</ul>
1.3.3 Example: Booking Category = Divyaang For a booking from Delhi to Mumbai:

By AC3Tier for Blind:

• Distance from Delhi to Mumbai = 1447km

• Base fare = 1447km * Rs. 0.5 / km = Rs. 723.50

• Loaded fare for AC3Tier = Rs. 723.50 * 2.50 = Rs. 1808.75 • Concession fare = Rs. 1808.75 * (1.00 – 0.75) = Rs. 452.1875

</div>
<div class="column">
40.00 = Rs. 1848.75 ≈ Rs. 1849/=

60.00 = Rs. 4762.75 ≈ Rs. 4763/=

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
<div class="layoutArea">
<div class="column">
40.00 = Rs. 1125.25 ≈ Rs. 1125/=

60.00 = Rs. 2411.375 ≈ Rs. 2411/=

</div>
</div>
</div>
<div class="page" title="Page 5">
<div class="layoutArea">
<div class="column">
• After adding the reservation charge, we get Rs. 452.1875 + Rs. 40.00 = Rs. 492.1875 ≈ Rs. 492/= (rounded)

By ACFirstClass for Cancer Patient:

<ul>
<li>Distance from Delhi to Mumbai = 1447km</li>
<li>Base fare = 1447km * Rs. 0.5 / km = Rs. 723.50</li>
<li>Loaded fare for ACFirstClass = Rs. 723.50 * 6.50 = Rs. 4702.75</li>
<li>Concession fare = Rs. 4702.75 * (1.00 – 0.50) = Rs. 2351.375</li>
<li>After adding the reservation charge, we get Rs. 2351.375 + Rs. 60.00 = Rs. 2411.375 ≈ Rs. 2411/= (rounded)</li>
</ul>
1.3.4 Example: Booking Category = Tatkal For a booking from Delhi to Mumbai:

By AC3Tier:

<ul>
<li>Distance from Delhi to Mumbai = 1447km</li>
<li>Base fare = 1447km * Rs. 0.5 / km = Rs. 723.50</li>
<li>Loaded fare for AC3Tier = Rs. 723.50 * 2.50 = Rs. 1808.75. This is the basic fare to be used computing tatkal charge</li>
<li>30% of basic fare = Rs. 1808.75 * 0.30 = Rs. 542.625</li>
<li>Tatkal charge = Rs. 400.00 (by maximum cap)</li>
<li>After adding the reservation charge, we get Rs. 1808.75 + Rs. 400.00 Rs. 40.00 = Rs. 2248.75 ≈ Rs. 2249/= (rounded)For a booking from Chennai to Bangalore:
By ACFirstClass:
</li>
</ul>
<ul>
<li>Distance from Chennai to Bangalore = 350km</li>
<li>Basefare=350km*Rs. 0.5/km=Rs. 175.00</li>
<li>Loaded fare for ACFirstClass = Rs. 175.00 * 6.50 = Rs. 1137.50</li>
<li>30% of basic fare = Rs. 1137.50 * 0.30 = Rs. 341.25</li>
<li>Tatkal charge = Rs. 0.00 (by minimum distance cap)</li>
<li>After adding the reservation charge, we get Rs. 1137.50 + Rs. 0.00 + Rs. 60.00 = Rs. 1197.50 ≈ Rs. 1198/= (rounded)</li>
</ul>
1.4 Master Data

While it will be nice to read the master data from master files at the start of the system run, it will be fine to hard-code these data for this assignment. However, the hard-coding should be done in limited, well-documented areas of the code so that it will be easy to change them as needed. These should be not hard-code inside the implementation of functions / methods.

</div>
</div>
<div class="layoutArea">
<div class="column">
5

</div>
</div>
</div>
<div class="page" title="Page 6">
<div class="layoutArea">
<div class="column">
1.4.1 Stations

</div>
</div>
<div class="layoutArea">
<div class="column">
IndianRailways has five Stations, namely: Mumbai, Delhi, Bangalore, Kolkata, and Chennai. The distances between the stations are given below:

</div>
</div>
<div class="layoutArea">
<div class="column">
Station Distance Matrix

From To Station Station Mumbai Delhi Bangalore Kolkata

</div>
</div>
<div class="layoutArea">
<div class="column">
Chennai

1338

1472

2180

</div>
</div>
<div class="layoutArea">
<div class="column">
Distance in KM

981

2014

</div>
</div>
<div class="layoutArea">
<div class="column">
Mumbai Mumbai Mumbai Mumbai

Delhi Delhi Delhi

Distance between a pair of stations is symmetric

1.4.2 Booking Classes

IndianRailways has eight booking classes as follows – shown with their respective attributes: *Booking Class Matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
X

</div>
<div class="column">
1447

X

</div>
</div>
<div class="layoutArea">
<div class="column">
2150

</div>
</div>
<div class="layoutArea">
<div class="column">
X

Kolkata X

</div>
</div>
<div class="layoutArea">
<div class="column">
Bangalore Bangalore

</div>
<div class="column">
1871

</div>
</div>
<div class="layoutArea">
<div class="column">
350 1659

</div>
</div>
<div class="layoutArea">
<div class="column">
Booking Class

ACFirstClass

(1A)

*ExecutiveChairCar

AC2Tier

(2A)

FirstClass

(FC)

AC3Tier

(3A)

ACChairCar

(CC)

Sleeper

(SL)

SecondSitting

(2S)

</div>
<div class="column">
Name *Fare Seat / Load Berth

Factor

AC 6.50 Berth First Class

Executive 5.00 Seat Chair Car

AC 4.00 Berth 2 Tier

First 3.00 Berth Class

AC 2.50 Berth 3 Tier

AC 2.00 Seat Chair Car

Sleeper 1.00 Berth Second 0.60 Seat

Sitting

</div>
<div class="column">
AC # of

Tiers

Yes 2 Yes 0 Yes 2 No 2 Yes 3 Yes 0 No 3 No 0

</div>
<div class="column">
Luxury / Ordinary

Luxury Luxury Ordinary Luxury Ordinary Ordinary Ordinary Ordinary

</div>
<div class="column">
*Reservation Charge (in Rs.)

</div>
</div>
<div class="layoutArea">
<div class="column">
60.00 60.00 50.00 50.00 40.00 40.00 20.00 15.00

</div>
</div>
<div class="layoutArea">
<div class="column">
1.4.3

</div>
</div>
<div class="layoutArea">
<div class="column">
• New booking classes may be added in future

• Fare load factors may change from time to time

• Reservation charges may change from time to time

• Luxury / Ordinary categorization may change according to tax rules

• Seat / Berth &amp; AC / non-AC classification, and # of tiers will not change in future • IRCTC Book Ticket

• Indian Railways fare classes explained

</div>
</div>
<div class="layoutArea">
<div class="column">
*Booking Categories

Tickets can be booked in the IndianRailways in one of six categories have the respective attributes:

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
</div>
<div class="page" title="Page 7">
<div class="layoutArea">
<div class="column">
Booking Name Concession

</div>
<div class="column">
Remarks

</div>
</div>
<div class="layoutArea">
<div class="column">
Category

General Ladies

SeniorCitizen Divyaang Tatkal PremiumTatkal

</div>
<div class="column">
General Ladies

Senior Citizen Divyaang

Tatkal

Premium Tatkal

</div>
<div class="column">
Factor

0.00 0.00

0.40 0.50 –

0.00 0.00

</div>
<div class="column">
General booking available to all

Special booking for ladies and 12− years male Applies for berth priority. No fare concession Special booking for 60+ years male

Special booking for 58+ years female

Special booking for the disabled

as charged by Disability Concession Matrix Priority booking 1 day before travel

as charged by Tatkal Charges Matrix Priority booking 1 day before travel

as charged by Tatkal Charges Matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
Booking Category Matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
• New booking categories may be added in future • Fare load factors may change from time to time • Processing fees may change from time to time

• Rail Fare Concession for Senior Citizens

• Rail Fare Concession for Disabled Persons

</div>
</div>
<div class="layoutArea">
<div class="column">
Disability Concession Factor Matrix

Booking Class Type of Disability

</div>
</div>
<div class="layoutArea">
<div class="column">
Blind Orthopaedically Handicapped

</div>
</div>
<div class="layoutArea">
<div class="column">
Cancer TB Patients Patients

0.50 0.00 0.75 0.00 0.50 0.00 0.75 0.75 1.00 0.00 1.00 0.00 1.00 0.75 1.00 0.75

Minimum Distance for charge (in Km)

<pre>                                                                       500
                                                                       250
                                                                       500
                                                                       500
                                                                       500
                                                                       250
                                                                       500
                                                                       100
</pre>
• The Tatkal Charges have been fixed as a percentage of fare at the rate of 10% of basic fare for second class (SecondSitting) and 30% of basic fare for all other classes subject to minimum and maximum as given above

• A Premium Tatkal ticket has same charge rules as above but is charged at double of Tatkal

• No tatkal charge is levied for travel below the minimum distance for charge

• Indian Railways Tatkal Scheme

</div>
</div>
<div class="layoutArea">
<div class="column">
ACFirstClass 0.50 ExecutiveChairCar 0.75 AC2Tier 0.50 FirstClass 0.75 AC3Tier 0.75 ACChairCar 0.75 Sleeper 0.75 SecondSitting 0.75

• Rail Fare Concession for Disabled Persons • Concession Rules

</div>
<div class="column">
0.50 0.75 0.50 0.75 0.75 0.75 0.75 0.75

</div>
</div>
<div class="layoutArea">
<div class="column">
Booking Class

</div>
<div class="column">
Minimum Tatkal Charges

</div>
<div class="column">
Maximum Tatkal Charges

</div>
</div>
<div class="layoutArea">
<div class="column">
Talkal Charges Matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
(in Rs.) (in Rs.)

</div>
</div>
<div class="layoutArea">
<div class="column">
ACFirstClass

ExecutiveChairCar

AC2Tier

FirstClass

AC3Tier

ACChairCar

Sleeper

SecondSitting 10.00 15.00

</div>
</div>
<div class="layoutArea">
<div class="column">
400.00 500.00 400.00 500.00 400.00 500.00 400.00 500.00 300.00 400.00 125.00 225.00 100.00 200.00

</div>
</div>
<div class="layoutArea">
<div class="column">
7

</div>
</div>
</div>
<div class="page" title="Page 8">
<div class="layoutArea">
<div class="column">
2 *Analysis of Specification

As discussed in SDLC and UML, the first target in analysis is to extract the Use Case and Class diagrams for

the system. Then build the other diagrams – Sequence, Communication, Activity, and State Machine.

2.1 *Use Case Diagram

We first analyze the specifications to identify the actors, use-cases, and the relationships in the problem. We also try to extract possible constraints on the design. Identification of the actors and use-cases for Use-Case Diagrams is left as a part of assignment exercise.

2.2 *Class Diagram

Next we need to identify the classes, attributes, methods, hierarchy, associations, relationships etc. to prepare the Class Diagram. While the overall and detailed Class Diagram will be left as an exercise in the assignment, we analyze to identify the classes and discuss various aspects of the classes to facilitate the process of design.

Our implementation language is pre-decided to be C++. So during analysis, we leave appropriate pointers for HLD and LLD in the context of C++. This is help in the translation of the Class Diagram into the C++ classes.

2.2.1 Summary of Polymorphisms in C++

Before delving into the actual task we present a summary of polymorphisms available in C++ (as was also discussed in the class). We shall make regular references to these.

C++ support the following four kinds of polymorphism.

<ul>
<li>Ad-hoc Polymorphism: Static polymorphism by overloading of methods. Available globally or on a non-virtual hierarchy (inheritance without virtual functions).</li>
<li>Inclusion Polymorphism: Dynamic polymorphism by overriding of methods on a polymorphic hierar- chy (inheritance with virtual functions)</li>
<li>Parametric Polymorphism: Static polymorphism by templates where type is used as parameter. This is using template meta-programming.This is often combined with Inclusion Polymorphism.</li>
<li>Coercion Polymorphism: Type casting. This would be grossly avoided.</li>
</ul>
2.2.2 Classes in Booking Software

We identify entities from the specification as classes. Also, we extract some abstract concepts as classes as we factor and normalize for our design.

<ul>
<li>*Class Station

Station is a simple data class with unique name.</li>
<li>*Class Date

The Date class needs to validate date from string format and check for equality, leap year etc. It alsoneeds to support computation of age and a span of a year.</li>
<li>*Class and Hierarchy of Gender

Gender is a simple type with Male and Female type constants or sub-types. For uniformilty of design, wecan model it by inclusion and parametric polymorphism with Gender being an abstract base class.</li>
<li>*Class RailwaysClass Railways should be a singleton and should contain the master data of stations and distances. The singleton should be constant as no station can be added and distances cannot be changed. Further, it needs to exclude duplication of Station and Station to Station distances.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
8

</div>
</div>
</div>
<div class="page" title="Page 9">
<div class="layoutArea">
<div class="column">
• *Class and Hierarchy of BookingClasses

*BookingClass needs redesign based on our experience in Assignment 3. It can be made more compact

and reuseable.

Different Booking Classes should be a polymorphic hierarchy rooted at BookingClasses which may be an abstract base class. Instead of making it a flat hierarchy, it would be good to make it a multi-level hierarchy. This would need identification of abstract base sub-classes that are aligned with one or more properties of the Booking Classes.

If multiple properties are used in organizing the hierarchy, then the model would need multiple inheritance. However, we do not want to use multiple inheritance for the associated complications and inefficiency. Rather, we would use single inheritance on the strongest property and use the rest as HAS-A with polymorphic value based on the leaf class.

Naturally, there can be two candidates for this as Fare Load Factor, # of Tiers, and Luxury / Ordinary are more like pure attributes and clearly not useful for hierarchy:

<ul>
<li>– &nbsp;AC or Non-AC: Air-condition leads to comfort level, and is not fundamental to travel. So this is a weak candidate.</li>
<li>– &nbsp;Seat or Berth: This is fundamental property for a rail travel. So this is a strong candidate.

So we may introduce several intermediate abstract base classes on the strong property and its closestassociated attribute, viz. the number of tiers.

*In Assignment 3, we made a multi-level hierarchy of BookingClasseses introducing intermediate abstract classes like Seat or Berth etc. using the strongest property while modeling the rest of the attributes by HAS-A. Clarifications sought during the assignment and post-implementation analyses tell us that there is no specific semantic interpretation or role for such abstract classes in terms of the business logic involved. So it may be more appropriate the treat all the properties as HAS-A and just model using a single level flat hierarchy rooted at BookingClass which may be an abstract base class. This is then turns out to be more of a static sub-typing situation and we can trade off pure inclusion polymorphism with inclusion and parametric polymorphism.

Further we may note that every concrete booking class has all fixed properties and there should be no need to construct more than one object for any of them. So there may be a singleton constant object for each which, kind of, will stand for its polymorphic type.

The hierarchy should be extensible in future as new booking classes are added.

*Additionally, as is discussed and explained below for the BookingCategory, the following attributes need to be maintained for a BookingClass for handling the Priority Booking as given in Talkal Charges Matrix in Section 1.4.3. As stated, these may change from time to time.

– Tatkal Load Factor: The factor by which premium is charged for the BookingClass.

– Minimum (Maximum) Tatkal Charge: Minimum (Maximum) Tatkal charge for the BookingClass. – Minimum Tatkal Distance: Minimum distance of travel to levy Tatkal charge for the BookingClass.

• *Class and Hierarchy of BookingCategory

Like BookingClasseses, different sub-categories of BookingCategory may be represented by a flat single level hierarchy or static sub-typing by inclusion and parametric polymorphism. Every leaf class, however, will need to implement an Eligibility policy as a polymorphic behaviour.

Here we come across an interesting issue. Regarding the role of BookingCategory in terms of determination of fare. How should we handle the general, concessional, and priority booking categories?

<ul>
<li>– &nbsp;General Booking has neither any concession nor any premium charge</li>
<li>– &nbsp;Concessional Booking has concessions based on a mix factors from BookingCategory, Booking-Class, and gender, age &amp; ability type (divyaangjan) of the Passenger</li>
<li>– &nbsp;Priority Booking attracts Tatkal charge depending on BookingClass and distance.It will be quite interesting to depict this information through Associations and Relationships in the UML Class Diagram and is left as an exercise.
While General Booking does not need any additional support, both concessional and priority booking would need further information representation and polymporphic computation.
</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
9

</div>
</div>
</div>
<div class="page" title="Page 10">
<div class="layoutArea">
<div class="column">
– Concessional Booking: Concession is a ternary relationship between BookingCategory, Booking- Class, and Passenger. This actually gets to be a quaternary relationship when we consider concessions due to disability which depends on the specific type of disability too.

So we can clearly see that we need to acknowledge Concessions and Divyaang (Disability) as key abstract concepts with appropriate polymorphic behavior to complete the modeling of BookingCat- egory.

– Priority Booking: In contrast to above, Tatkal charges depend on the BookingClass and can be subsumed in it by normalization3. Hence, we simply add the data members in BookingClass above.

• *Class and Hierarchy of Divyaang (Disabled)

Disability Concession Factor Matrix in Section 1.4.3 tell us that four types of disability are to be considered for Divyaang BookingCategory. So different sub-categories of Divyaang may be represented by a flat single level hierarchy or static sub-typing by inclusion and parametric polymorphism.

• *Class and Hierarchy of Concessions

For keeping the information of (selective) concessions for General as well as Concessional Booking ac- cording to respective BookingCategorys, a Concessions hierarchy may be created. For this, we note that concession is dependent on BookingCategory, BookingClass, and gender, age &amp; ability type (divyaang- jan) of the Passenger as given in Booking Category Matrix and Disability Concession Factor Matrix in Section 1.4.3. Let us summarize the dependence of these information in the table below:

</div>
</div>
<div class="layoutArea">
<div class="column">
Concessions Dependency on class class based on

BookingCategory BookingClasses Passenger Divyaang

</div>
<div class="column">
Remarks

No concession

No concession for now Concession based on gender Concession as in matrix

</div>
</div>
<div class="layoutArea">
<div class="column">
General Ladies SeniorCitizen Divyaang

</div>
<div class="column">
No No No No Yes No No Yes No Yes Yes Yes

</div>
</div>
<div class="layoutArea">
<div class="column">
Tatkal categories are not considered as there is no concession

</div>
</div>
<div class="layoutArea">
<div class="column">
Clearly, no common interface can compute (extract) the concession across different Concessions classes in the hierarchy as specialized from a base class Concessions. So we need to model it by flat single level ad-hoc polymorphism and there is no logical scope to use inclusion or parametric polymorphism. Consequently, the base class cannot be abstract either.

• *Class and Hierarchy of Booking

Booking may be treated as a simple concrete class with the parameters mentioned in the specification.

We may keep Passenger as a null-able default for future extension.

Booking may be also be modeled as a polymorphic base class as with the introduction of Passenger in

future it is likely to lead to a booking hierarchy.

*In assignment 3, Booking could be a simple concrete class because there was only one algorithm (business logic) to compute fare that used some attribute values of the respective BookingClass. The model now has to improve, because the business logic of Booking depends on the BookingCategory.

So Booking can be an abstract base class rooting an inclusion and parametric polymorphic hierarchy that parallels the hierarchy of the BookingCategory.

Though it looks like a cool solution, it get may get tricky in the details. Note that we need to create an object of the appropriate Booking sub-class based on its BookingCategory. This means we need to virtualize the construction process which is not possible. The inclusion polymorphism of the Booking hierarchy can be used to invoke the appropriate fare computation business logic only after we have the right Booking class object for the BookingCategory.

• *Class and Hierarchy of Passenger

Class Passenger may be an empty abstract base class. Since we are not going to use it, we would not need to make objects for the same. However, it would be good to have it as a polymorphic base for future extension, especially since the specification talks of various categories of passengers.

3Normalization is the process of organizing the data in the database. Normalization is used to minimize the redundancy from a relation or set of relations. The normal form is used to reduce redundancy from the database table. You will learn about these in depth in your DBMS course.

</div>
</div>
<div class="layoutArea">
<div class="column">
10

</div>
</div>
</div>
<div class="page" title="Page 11">
<div class="layoutArea">
<div class="column">
•

</div>
<div class="column">
*The Passenger class is a simple data class that needs to keep data member values as specified. Of course, it will need a number of validation methods for the constraints specified for its data members like name, age, aadhaar (syntax only), etc.

*Class and Hierarchy of Exceptions

Since erroneous inputs and conditions are allowed now, we need to design a hierarchy of Exceptions classes

derived from std::exception.

Fundamentally, we can identify the following top level Exceptions types:

<ul>
<li>– &nbsp;Bad Date: Format or date validity errors. This is used by several classes.</li>
<li>– &nbsp;Bad Railways: Errors in master data of Bad Railways. This may be specialized into a number specific sub-classes for the types of error like Station name and duplication, distance duplication etc.

This should be caught in the application.</li>
<li>– &nbsp;Bad Passenger: Errors in data of Passenger. This may be specialized into a number specific sub- classes for the types of error like name, age, aadhaar, mobile, etc.

This should be caught in the application.</li>
<li>– &nbsp;Bad Booking: Errors in data of Booking. This may be specialized into a number specific sub-classes for the types of error like date of booking, ladies, senior citizen, etc.

This should be caught in the application.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
2.3

3 High Level Design

Based on the analysis, now we carry out the High Level Design (HLD) below for Classes, Interfaces, Constants, Statics, Exceptions, and overall design considerations.

3.1 Design Principles

The following design principles may be adhered to in the HLD:

• Flexible &amp; Extensible Design

<ul>
<li>– &nbsp;The design should be flexible. That is, it should be easy to change the changeable parameters (like base rate, load factor etc.) easily from the Application space. This should should not need re-building of the library of classes.</li>
<li>– &nbsp;The design should be extensible. That is, it should be easy to add new behaviour (classes) wherever indicated in the specification (like Booking Classes, Booking, Passenger, etc.). This should not require a re-coding of the existing applications.• Minimal Design

– Only the stated models and behaviour should be coded. No extra class or method should be coded.

– Less code, less error principle to be followed. • *Reliable &amp; Safe Design

– Reliability should be a priority. Everything should work as designed and coded.

– Data members, methods and objects should be made constant wherever possible.

– Parameters should be appropriately defaulted wherever possible

– The system should never be allowed to go into an inconsistent state.

– All possible errors of data and processing must be appropriately thrown and caught handled.

• Testable Design
</li>
</ul>
<ul>
<li>– &nbsp;Every class should support the output streaming operator for checking intermittent output if needed.</li>
<li>– &nbsp;Every class should be tested with an appropriate test application for its unit functionality (Sec- tion 6.1).</li>
<li>– &nbsp;TestApplications(Section6.2)andregressiontestsuitesshouldbedesignedfortestingtheapplication on (at least) the common scenarios of use.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
*Sequence, Communication, Activity &amp; State Machine Diagrams Left as a part of assignment exercise.

</div>
</div>
<div class="layoutArea">
<div class="column">
11

</div>
</div>
</div>
<div class="page" title="Page 12">
<div class="layoutArea">
<div class="column">
3.2 *Classes

*The classes and hierarchy as outlined in Requirement Specification (Section 1.1) and Analysis (Section 2), can

be put in HLD.

<ul>
<li>Class Station HAS-A name.</li>
<li>Class Railways is a singleton called IndianRailways. It has a collection of the Stations and their mutual distances. IndianRailways is a constant object.</li>
<li>Class Date is discussed in the lecture modules.</li>
<li>Class BookingClasses HAS-A loadFactor. Remaining attributes may be encoded on the methods in thehierarchy classes.</li>
<li>Class Booking HAS-A fromStation, toStation date, and bookingClass from the booking request where every station name, date and booking class are assumed to have been given correctly. Further it HAS-A fare computed and PNR allocated. Optionally, it may HAS-A bookingStatus (which would be true for this assignment always) and bookingMessage (which may be “BOOKING SUCCEEDED” for this assignment always).Booking should support Passenger as a null-able parameter for future extension.</li>
<li>*Make data members as const (or const reference) wherever possible.</li>
<li>You may add any class, any data member to a class, or any hierarchy as you need for implementation. Justify your design choice for them.</li>
</ul>
3.2.1 Modeling Sub-Types

During the analysis, we see that there are number of classes and sub-classes including Gender, BookingClass, BookingCategory, and Divyaang where static sub-typing exists as the sub-classes mostly have the same set of data members and methods. Even the Booking can be modeled with this. Specifically, we observe the following:

<ol>
<li>Data members are constants at many places and takes by static values (specific to the sub-class).</li>
<li>Methods are mostly identical in algorithm and differ in static data.</li>
<li>In a number of cases, methods need to be invoked by dynamic dispatch to support a uniform type interface in the application.</li>
<li>Conceptually, in most cases, a single-level flat hierarchy with an abstract base class and concrete sub- classes suffice the representation.</li>
<li>Most of the classes also represent static concepts. Hence, it is desirable that only a single constant object of the class should be constructed that can represent the type and be used as a placeholder everywhere for type consistency.</li>
</ol>
This leads to the question of which form/s of polymorphism in C++ should we use to model the hierarchy. Note that we have already decided to use a static hiearchy with ad-hoc polymorphism for Concessions.

If we use inclusion polymorphism, we have a greater flexibility for hierarchy along with dynamic dispatch based on the sub-class type, but the code bloats. This is good for (3), (4) &amp; (5), but not (1) &amp; (2).

If we use parametric polymorphism, it is relatively difficult to have flexible hierarchy or have dynamic dispatch, but we can have a more compact code with better reuse (and less code to actually write). This is good for (1), (2) &amp; (5), but not (3) &amp; (4).

So to get the best of both approaches, we may opt for a inclusion polymorphism of one level and have parametric polymorphism for the alike leaf classes. To understand the approaches better, let us work out the example for the design of Gender concept which has two sub-types Male and Female. We first model by inclusion polymor- phism and then by parametric polymorphism and for both cases check the way to write the applications.

By Inclusion Polymorphism

We code Gender as follows: Header File

</div>
</div>
<div class="layoutArea">
<div class="column">
12

</div>
</div>
</div>
<div class="page" title="Page 13">
<div class="layoutArea">
<div class="column">
<pre>// Gender.h
#ifndef __GENDER_H
#define __GENDER_H
</pre>
<pre>#include &lt;string&gt;
using namespace std;
</pre>
<pre>// Abstract Base Class - Concept of Gender
class Gender {
</pre>
<pre>    const string&amp; name_; // Name of the gender
protected:
</pre>
<pre>    Gender(const string&amp; name) : name_(name) { }
</pre>
<pre>    virtual ~Gender() { }
public:
</pre>
<pre>    const string&amp; GetName() const { return name_; }
</pre>
<pre>    virtual const string GetTitle() const = 0; // Salutation specific to gender
</pre>
<pre>    static bool IsMale(const Gender&amp;); // Checking and matching gender
};
</pre>
<pre>// Male class - specialized gender
class Male : public Gender {
</pre>
<pre>    Male() : Gender(Male::sName) {}
    static const string sName; // Name "Male" for this gender sub-type
</pre>
<pre>public:
    static const Gender&amp; Type() { // Singleton of Male that represents the type Male
</pre>
<pre>        static const Male theObj; // May be non-const if the type has changeable behavior
</pre>
<pre>        return theObj;
    }
</pre>
<pre>    const string GetTitle() const   // Dynamic dispatch
</pre>
<pre>    { return "Mr."; }               // Salutation is hard-coded - may be taken out as static
};
</pre>
<pre>// Female class - specialized gender
class Female : public Gender {
</pre>
<pre>    Female() : Gender(Female::sName) { }
    static const string sName; // Name "Female" for this gender sub-type
</pre>
<pre>public:
    static const Gender&amp; Type() { // Singleton of Female that represents the type Female
</pre>
<pre>        static const Female theObj; // May be non-const if the type has changeable behavior
</pre>
<pre>        return theObj;
    }
</pre>
<pre>    const string GetTitle() const   // Dynamic dispatch
</pre>
<pre>    { return "Ms."; }               // Salutation is hard-coded - may be taken out as static
};
</pre>
<pre>inline bool Gender::IsMale(const Gender&amp; g) { return &amp;g == &amp;Male::Type(); }
#endif // __GENDER_H
</pre>
Note that there is significant duplication of code between Male and Female class codes. Source File

<pre>// Gender.cpp
#include &lt;string&gt;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
13

</div>
</div>
</div>
<div class="page" title="Page 14">
<div class="layoutArea">
<div class="column">
<pre>using namespace std;
#include "Gender.h"
</pre>
<pre>// Names defined as static constants
const string Male::sName = "Male";
const string Female::sName = "Female";
</pre>
We are now ready to use the above classes.

Application File

<pre>// Gender_App.cpp
#include &lt;string&gt;
using namespace std;
</pre>
<pre>#include "Gender.h"
</pre>
<pre>class Person {
    const string name_;
    const Gender&amp; gender_;
</pre>
<pre>public:
    Person(
</pre>
<pre>        const string&amp; name,
        const Gender&amp; gender) : // Singleton constant Gender sub-class object
        name_(name), gender_(gender) {}
</pre>
<pre>    friend ostream&amp; operator&lt;&lt;(ostream&amp; os, const Person&amp; p) {
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
} };

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>os &lt;&lt; p.gender_.GetTitle() &lt;&lt; " "
   &lt;&lt; p.name_ &lt;&lt; " is a "
   &lt;&lt; p.gender_.GetName()
</pre>
</div>
<div class="column">
<pre>// Dynamic dispatch based on gender type
// Name set for the Person
// Static  dispatch on Gender to get the
// name of the gender
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>   &lt;&lt; endl;
return os;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>int main() {
    Person p1("Ramen Bag",
</pre>
<pre>        Male::Type());
    Person p2("Elisa Tang",
</pre>
<pre>        Female::Type());
</pre>
<pre>    cout &lt;&lt; p1;
    cout &lt;&lt; p2;
</pre>
return 0; }

Output:

Mr. Ramen Bag is a Male

<pre>Ms. Elisa Tang is a Female
</pre>
</div>
<div class="column">
<pre>// Type-safe expression of Male
// Type-safe expression of Female
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
By Parametric Polymorphism

Now we code Gender as follows using parametric polymorphism with inclusion polymorphism: Header File

<pre>#ifndef __GENDER_H
#define __GENDER_H
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
14

</div>
</div>
</div>
<div class="page" title="Page 15">
<div class="layoutArea">
<div class="column">
<pre>#include &lt;string&gt;
using namespace std;
</pre>
<pre>// Forward declaration of templatized class
template&lt;typename T&gt;
class GenderTypes;  // Generic Gender type to generate specific genders
</pre>
<pre>// Generic gender type
class Gender { // Abstract Base Class
</pre>
<pre>    const string&amp; name_; // Name of the Gender
</pre>
<pre>    // Tag types - to instantiate the template
    // Note that these names are placeholders only and are not exposed outside the class
    // Also they are put inside the class for not cluttering the global namespace
    struct MaleType {};
    struct FemaleType {};
</pre>
<pre>protected:
    Gender(const string&amp; name) : name_(name) {}
    virtual ~Gender() { }
</pre>
<pre>public:
    const string&amp; GetName() const { return name_; }
</pre>
<pre>    virtual const string GetTitle() const = 0; // Salutation specific to gender
    static bool IsMale(const Gender&amp;); // Checking and matching gender
</pre>
<pre>    // Enumerated types - the target sub-types
    typedef GenderTypes&lt;MaleType&gt; Male;
    typedef GenderTypes&lt;FemaleType&gt; Female;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
};

<pre>// Specific gender  types
template&lt;typename T&gt;
class GenderTypes : public Gender {
</pre>
<pre>    static const string sName;
    static const string sSalutation;
</pre>
</div>
<div class="column">
<pre>// Respective name of the gender
// Respective salutation for the gender
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>    GenderTypes(const string&amp; name = GenderTypes&lt;T&gt;::sName) : Gender(name) { }
    ~GenderTypes() { }
</pre>
<pre>public:
    // Singleton object - placeholder for the respective type
    static const GenderTypes&lt;T&gt;&amp; Type() {
</pre>
<pre>        static const GenderTypes&lt;T&gt; theObject;  // May be non-const for changeable behavior
</pre>
<pre>        return theObject;
    }
</pre>
<pre>    const string GetTitle() const           // Dynamic dispatch
</pre>
<pre>    { return GenderTypes&lt;T&gt;::sSalutation; } // Salutation parametrized by static
};
</pre>
<pre>inline
bool Gender::IsMale(const Gender&amp; g) { return &amp;g == &amp;Gender::Male::Type(); }
#endif // __GENDER_H
#endif // __GENDER_H
</pre>
Note that the earlier duplication of code between Male and Female class codes are now removed and refactored into the template code. It improves code reuse. In this small example, however, the reduction in LoC is not

</div>
</div>
<div class="layoutArea">
<div class="column">
15

</div>
</div>
</div>
<div class="page" title="Page 16">
<div class="layoutArea">
<div class="column">
visible (actually it bloats). When we have more sub-classes, like for BookingClass, we shall have significant code reduction and reuse.

Source File

<pre>// Gender.cpp
</pre>
<pre>#include &lt;string&gt;
using namespace std;
</pre>
<pre>#include "Gender.h"
</pre>
<pre>// Names defined as static constants
const string Gender::Male::sName = "Male";
const string Gender::Female::sName = "Female";
</pre>
<pre>// Salutations defined as static constants
const string Gender::Male::sSalutation = "Mr.";
const string Gender::Female::sSalutation = "Ms.";
</pre>
Application File

Note that only change in the application is in the scoping of the sub-types as Male (Female) becomes Gender::Male (Gender::Female). This is even more type-safe as the global namespace is not cluttered.

<pre>// Gender_App.cpp
#include &lt;iostream&gt;
#include &lt;string&gt;
using namespace std;
</pre>
<pre>#include "Gender.h"
</pre>
<pre>class Person {
    const string name_;
    const Gender&amp; gender_;
</pre>
<pre>public:
    Person(
</pre>
<pre>        const string&amp; name,
        const Gender&amp; gender) : // Singleton constant Gender sub-class object
        name_(name), gender_(gender) {}
</pre>
<pre>    friend ostream&amp; operator&lt;&lt;(ostream&amp; os, const Person&amp; p) {
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
} };

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>os &lt;&lt; p.gender_.GetTitle() &lt;&lt; " "
   &lt;&lt; p.name_ &lt;&lt; " is a "
   &lt;&lt; p.gender_.GetName()
</pre>
<pre>   &lt;&lt; endl;
return os;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>                                            // Dynamic dispatch based on gender type
                                            // Name set for the Person
                                            // Static  dispatch on Gender to get the
                                            // name of the gender
</pre>
<pre>                                 // Type-safe expression of Male - note the change in scoping
        Gender::Female::Type()); // Type-safe expression of Female - note the change in scoping
</pre>
<pre>    cout &lt;&lt; p1;
    cout &lt;&lt; p2;
</pre>
return 0; }

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>int main() {
    Person p1("Ramen Bag",
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>    Gender::Male::Type());
Person p2("Elisa Tang",
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
16

</div>
</div>
</div>
<div class="page" title="Page 17">
<div class="layoutArea">
<div class="column">
Output:

Mr. Ramen Bag is a Male

<pre>Ms. Elisa Tang is a Female
</pre>
So we may use the above inclusion-parametric polymorphism for Gender, BookingClass, Book- ingCategory, Divyaang, and Booking. And we use ad-hoc polymorphism for Concessions and Exceptions. Finally, Date, Station, Railways, and Passenger will have no hierarchy.

3.2.2 Virtual Construction Idiom

We know that constructor for a class is static and it cannot be virtual. But conceptually, we come across such situations often when we need to choose between a set of sub-classes based on the information of some other types. For example, there are as many Booking sub-classes as there are BookingCategorys – one for each. Now given a BookingCategory in the input, how do we invoke the constructor of the right sub-class of Booking. The situation is again that of a type-switch, except here based on the type of one hierarchy (BookingCategory), we need to create an appropriate object of another (Booking) hierarchy. Notionally, we need to virtualize the construction process. A naive solution would be to explicitly check the type of BookingCategory object, and create corresponding Booking class object which suffers from the usual evils of being type unsafe.

Let us consider a tiny example to understand the problem and the solution. Consider an application for a Swimming Pool Slot booking where separate slots (and pools) based on gender. So we have a PoolSlot abstract class with MalePoolSlot FemalePoolSlot as respective specializations. We use our earlier design of Gender and produce the following code using an explicit type-switch in PoolSlot::ReservePoolSlot() function:

<pre>#include &lt;iostream&gt;
#include &lt;string&gt;
using namespace std;
</pre>
<pre>class Gender {
    const string&amp; name_;
</pre>
<pre>protected:
    Gender(const string&amp; name) : name_(name) { }
    virtual ~Gender() { }
</pre>
<pre>public:
    const string&amp; GetName() const { return name_; }
    static bool IsMale(const Gender&amp;);  // In a good OOP design we must not have /
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>};
class Male : public Gender {
</pre>
<pre>    Male() : Gender(Male::sName) {}
    static const string sName;
</pre>
<pre>public:
    static const Gender&amp; Type() {
</pre>
<pre>        static const Male theObj;
</pre>
<pre>        return theObj;
    }
</pre>
<pre>};
class Female : public Gender {
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>    Female() : Gender(Female::sName) { }
    static const string sName;
</pre>
<pre>public:
    static const Gender&amp; Type() {
</pre>
<pre>        static const Female theObj;
</pre>
<pre>        return theObj;
    }
</pre>
};

<pre>// Explicit checking of type
bool Gender::IsMale(const Gender&amp; g) { return &amp;g == &amp;Male::Type(); }
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// need such an interface!
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
17

</div>
</div>
</div>
<div class="page" title="Page 18">
<div class="layoutArea">
<div class="column">
<pre>// Names defined as static constants
const string Male::sName = "Male";
const string Female::sName = "Female";
</pre>
<pre>class PoolSlot {
protected:
</pre>
<pre>    const string name_;
</pre>
<pre>    PoolSlot(const string&amp; name) : name_(name) { }
public:
</pre>
<pre>    ~PoolSlot() {}
</pre>
<pre>    static PoolSlot* ReservePoolSlot(const string&amp; name, const Gender&amp; g);
};
</pre>
<pre>class MalePoolSlot : public PoolSlot {
public:
</pre>
<pre>    MalePoolSlot(const string&amp; name) : PoolSlot(name) {
        cout &lt;&lt; "MalePoolSlot created for " &lt;&lt; name_ &lt;&lt; endl;
</pre>
} };

<pre>class FemalePoolSlot : public PoolSlot {
public:
</pre>
<pre>    FemalePoolSlot(const string&amp; name) : PoolSlot(name) {
        cout &lt;&lt; "FemalePoolSlot created for " &lt;&lt; name_ &lt;&lt; endl;
</pre>
} };

<pre>PoolSlot* PoolSlot::ReservePoolSlot(const string&amp; name, const Gender&amp; g) {
    PoolSlot* p = 0;
</pre>
<pre>    // This is the type-switch that we must avoid
    // This is error-prone, not scalable, and type-unsafe
    if (Gender::IsMale(g))
</pre>
<pre>        p = new MalePoolSlot(name);
    else
</pre>
<pre>        p = new FemalePoolSlot(name);
</pre>
return p; }

<pre>int main() {
    PoolSlot* p1 = PoolSlot::ReservePoolSlot("Ramen Bag", Male::Type());
    PoolSlot* p2 = PoolSlot::ReservePoolSlot("Elisa Tang", Female::Type());
</pre>
<pre>    delete p1;
    delete p2;
</pre>
return 0; }

Now we refine the design:

<ol>
<li>Drop the explicit type-checking function Gender::IsMale().</li>
<li>Introduce a virtual function Gender::CreatePoolSlot() for dynamically switching type based on gender</li>
<li>Replace explicit type-switch in PoolSlot::ReservePoolSlot() by dynamic dispatch on gender type</li>
<li>Construct appropriate type of PoolSlot object on overridden versions of Male::CreatePoolSlot() and Female::CreatePoolSlot() respectively.</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>#include &lt;iostream&gt;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
18

</div>
</div>
</div>
<div class="page" title="Page 19">
<div class="layoutArea">
<div class="column">
<pre>#include &lt;string&gt;
using namespace std;
</pre>
<pre>class PoolSlot;
</pre>
<pre>class Gender {
    const string&amp; name_;
</pre>
<pre>protected:
    Gender(const string&amp; name) : name_(name) { }
    virtual ~Gender() { }
</pre>
<pre>public:
    const string&amp; GetName() const { return name_; }
    //static bool IsMale(const Gender&amp;);
    virtual PoolSlot* CreatePooSlot(const string&amp; name) const = 0;
</pre>
<pre>};
class Male : public Gender {
</pre>
<pre>    Male() : Gender(Male::sName) {}
    static const string sName;
</pre>
<pre>public:
    static const Gender&amp; Type() {
</pre>
<pre>        static const Male theObj;
</pre>
<pre>        return theObj;
    }
</pre>
<pre>    PoolSlot* CreatePooSlot(const string&amp; name) const;
};
</pre>
<pre>class Female : public Gender {
    Female() : Gender(Female::sName) { }
    static const string sName;
</pre>
<pre>public:
    static const Gender&amp; Type() {
</pre>
<pre>        static const Female theObj;
</pre>
<pre>        return theObj;
    }
</pre>
<pre>    PoolSlot* CreatePooSlot(const string&amp; name) const ;
};
</pre>
<pre>//bool Gender::IsMale(const Gender&amp; g) { return &amp;g == &amp;Male::Type(); }
</pre>
<pre>// Names defined as static constants
const string Male::sName = "Male";
const string Female::sName = "Female";
</pre>
<pre>class PoolSlot {
protected:
</pre>
<pre>    const string name_;
</pre>
<pre>    PoolSlot(const string&amp; name) : name_(name) { }
public:
</pre>
<pre>    ~PoolSlot() {}
</pre>
<pre>    static PoolSlot* ReservePoolSlot(const string&amp; name, const Gender&amp; g);
};
</pre>
<pre>class MalePoolSlot : public PoolSlot {
public:
</pre>
<pre>    MalePoolSlot(const string&amp; name) : PoolSlot(name) {
        cout &lt;&lt; "MalePoolSlot created for " &lt;&lt; name_ &lt;&lt; endl;
</pre>
}

</div>
</div>
<div class="layoutArea">
<div class="column">
19

</div>
</div>
</div>
<div class="page" title="Page 20">
<div class="layoutArea">
<div class="column">
};

</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// Creates MalePoolSlot object
PoolSlot* Male::CreatePooSlot(const string&amp; name) const {
</pre>
<pre>    return new MalePoolSlot(name);
}
</pre>
<pre>class FemalePoolSlot : public PoolSlot {
public:
</pre>
<pre>    FemalePoolSlot(const string&amp; name) : PoolSlot(name) {
        cout &lt;&lt; "FemalePoolSlot created for " &lt;&lt; name_ &lt;&lt; endl;
</pre>
} };

<pre>// Creates FemalePoolSlot object
PoolSlot* Female::CreatePooSlot(const string&amp; name) const {
</pre>
<pre>    return new FemalePoolSlot(name);
}
</pre>
<pre>PoolSlot* PoolSlot::ReservePoolSlot(const string&amp; name, const Gender&amp; g) {
    //PoolSlot* p = 0;
    //if (Gender::IsMale(g))
    //    p = new MalePoolSlot(name);
</pre>
<pre>    //else
    //    p = new FemalePoolSlot(name);
</pre>
//return p;

<pre>    // Dynamic dispatch takes care of the type switch on gender
</pre>
<pre>    return g.CreatePooSlot(name);
}
</pre>
<pre>int main() {
    PoolSlot* p1 = PoolSlot::ReservePoolSlot("Ramen Bag", Male::Type());
    PoolSlot* p2 = PoolSlot::ReservePoolSlot("Elisa Tang", Female::Type());
</pre>
<pre>    delete p1;
    delete p2;
</pre>
return 0; }

Effectively, we achieve virtualization in construction based on an object hierarchy. However, the cost is – the design of the Gender now gets tightly coupled with the design of PoolSlot (which should not have been). There would the work arounds for that too – but that’s later.

So now we are ready to do a good design for Booking class hierarchy. 3.3 Interfaces

*The interfaces, as outlined in Requirement Specification (Section 1.1) and Analysis (Section 2), can be put in HLD.

<ul>
<li>Constructors / Destructors: Proper constructor and destructor for every class</li>
<li>Copy Functions: Provide user-defined Copy Constructor and / or Copy Assignment Operator for a classif used in the design (should not be needed). Otherwise, block them.</li>
<li>Provide output streaming operator for every class to help output process as well as debugging</li>
<li>Class Station to have GetName() for accessing its name and GetDistance(.) to get distance to another station.</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
20

</div>
</div>
</div>
<div class="page" title="Page 21">
<div class="layoutArea">
<div class="column">
<ul>
<li>Class Railways to have GetDistance(., .) to get distance between a pair of stations. It should also have proper interface for making it a singleton IndianRailways</li>
<li>Class BookingClasses to have GetLoadFactor(), GetName(), IsSitting(), IsAC(), GetNumberOfTiers(), and IsLuxury() to get access to various BookingClasses properties. Depending on the polymorphic hierarchy, these methods may be non-polymorphic and / or polymorphic (and in some case pure) in BookingClasses and its various derived classes. Consider making them const methods.</li>
<li>Class Booking to have ComputeFare() to implement the fare computation logic. Should it be virtual (polymorphic) for future extensions?</li>
<li>*Make methods const wherever possible.</li>
<li>You may add any interface to a class (or private / protected methods) as you need for implementation.Justify your design choice for them.
3.4 Constants

*Various static constants as outlined in Requirement Specification (Section 1.1), Master Data (Section 1.4), and Analysis (Section 2), can be put in HLD.

The following should be static constants in appropriate classes: • Load Factors of various BookingClasses

• Base Fare Rate: Rs. 0.50 / km

• AC Surcharge: Rs. 50.00

• Luxury Tax: 25% on booking amount 3.5 Statics

*Various static data members as outlined in Requirement Specification (Section 1.1), Master Data (Section 1.4), and Analysis (Section 2), can be put in HLD.

<ul>
<li>Class Date to have month and day names.</li>
<li>Class Railways to have sStations (list of stations) and sDistStations (distance between stations).</li>
<li>Class BookingClasses to have load factors.</li>
<li>Class Booking to have sBaseFarePerKM, sBookings (list of bookings done), sBookingPNRSerial (next available PNR), sACSurcharge, and sLuxuryTaxPercent</li>
<li>You may add any static to a class as you need for implementation.</li>
</ul>
</li>
</ul>
3.6 *Errors &amp; Exceptions

The design should take care of extensive validations for data and consistency of business logic. In this regard the following points may be noted:

• Date validations should include (may have more):

– All dates should be valid. For example, 29/02/2021 or 31/04/2020 should be declared invalid.

– Range of valid years would be 1900 to 2099

• Station validations should include (may have more):

– name cannot be empty

• Railways validations should include (may have more):

<ul>
<li>– &nbsp;No duplicate Station name would be allowed</li>
<li>– &nbsp;Distance must be defined between every pair of Stations. The definition is considered symmetric -so only one direction should given.</li>
<li>– &nbsp;No duplicate distance definition is allowed</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
21

</div>
</div>
</div>
<div class="page" title="Page 22">
<div class="layoutArea">
<div class="column">
•

</div>
<div class="column">
– Distance between two same Stations is not allowed Passenger validations should include (may have more):

<ul>
<li>– &nbsp;At least one of first name and last name must be non-empty. middle name may be empty.</li>
<li>– &nbsp;dateOfBirth must precede dateOfReservation.</li>
<li>– &nbsp;gender must be male or female. It must be valid by input. That is, it should not be possible to input a wrong gender.</li>
<li>– &nbsp;aadhaar # is 12 digit. It should be validated for absence of non-digit and length.</li>
<li>– &nbsp;mobile # is 10 digit. It should be validated, if provided, for absence of non-digit and length.</li>
<li>– &nbsp;disability type must be valid by input.</li>
<li>– &nbsp;disabilityID #: Number of the divyangjan ID (optional)All Booking requests are taken to be correct. That is, the Staions as mentioned – do exist, the Date is valid (in future), and no invalid BookingClass is requested
Booking validations should include (may have more):

<ul>
<li>– &nbsp;fromStation and toStation must be valid (pre-existing). The distance between them must be pre-set.</li>
<li>– &nbsp;dateOfBooking must be later than dateOfReservation and within one year from it.</li>
<li>– &nbsp;bookingClass must be valid by input. That is, it should not be possible to input a wrong bookingClass to the request.</li>
<li>– &nbsp;bookingCategory must be valid by input. That is, it should not be possible to input a wrong booking- Category to the request.</li>
<li>– &nbsp;passenger data must be consistent with the bookingCategory.</li>
<li>– &nbsp;All valid booking requests can be served.BookingClass, BookingCategory, Concessions, and Divyaang are constructed from static data and can be assumed to be free of errors.
If the construction of an object of a class has possibility of exception due to erroneous inputs, the same should be checked in a separate static function before invoking the constructor. This helps follow the guideline that no exception would be thrown from a constructor.

The following principle may be followed in error management:

<ul>
<li>– &nbsp;Every error must be properly handled and meaningfully reported.</li>
<li>– &nbsp;If there are more than one validation failures, the system should attempt to report as many of them as possible in a single run.</li>
<li>– &nbsp;All validations and reporting should be based on exceptional design clearly separating the normal flow from the exception flow.</li>
<li>– &nbsp;An appropriate hierarchy of exception classes may be designed for the error management. In no case, the system may be allowed to go to an inconsistent state and / or crash. There is no error in input, processing, or output.No error or exception handling to be incorporated in the design for this assignment. However, structure the code flow well so that they can be incorporated later with minimal changes (adhering to the need of flexibility).
Low-Level Design
</li>
</ul>
</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
• •

</div>
</div>
<div class="layoutArea">
<div class="column">
• •

•

• • •

</div>
</div>
<div class="layoutArea">
<div class="column">
4

</div>
</div>
<div class="layoutArea">
<div class="column">
Based on the High Level Design (HLD), we now perform the Low Level Design (LLD). LLD makes use of the specific constructs and idioms of C++.

</div>
</div>
<div class="layoutArea">
<div class="column">
22

</div>
</div>
</div>
<div class="page" title="Page 23">
<div class="layoutArea">
<div class="column">
4.1 Design Principles

The following design principles may be adhered to in the LLD:

• Encapsulation

<ul>
<li>– &nbsp;Maximize encapsulation for every class</li>
<li>– &nbsp;Use private access specifier for all data members that are not needed by derived classes, if any. Use protected otherwise.</li>
<li>– &nbsp;Use public access specifier for interface methods and static constants and friend functions only. • STL Containers– Use STL containers (like vector, map, hashmap, list, etc.) and their iterators. Do not use arrays – Use iterators for STL containers. Do not use bare for loops.
• Pointers &amp; References

<ul>
<li>– &nbsp;Minimize the use of pointers. Use pointers only if you need null-able entities</li>
<li>– &nbsp;If you use pointer for dynamically allocated objects (should be minimized), remember to delete at an appropriate position.</li>
<li>– &nbsp;Use const reference wherever possible.</li>
</ul>
</li>
</ul>
4.2 Design of Classes, Data Members &amp; Methods

This is left as an exercise in the assignment. Design based on the HLD and the principles and document well.

5 Implementation

After completing the LLD, we perform the coding (implementation). In this we adhered to a set of basic guidelines and code organization.

5.1 Basic Coding Guidelines

An indicative set of guidelines are listed in Section A. You may add more on your own. 5.2 *Code Organization

Ideally, the definition of every class (or hierarchy) should be put in a corresponding .h file with the static definitions and method implementations in the respective .cpp. The application should be in Application.cpp file. However, for simplicity, it would be acceptable if all the codes are put in the Application.cpp file with the application.

The code should be properly organized according to the following guidelines:

</div>
</div>
<div class="layoutArea">
<div class="column">
6

</div>
</div>
<div class="layoutArea">
<div class="column">
1. 2. 3.

</div>
<div class="column">
Every major class &lt;classname&gt;, and the hierarchy related to it, should be written in header file classname.h. Small and frequently invoked methods should also be inlined in this file.

The source or implementation file classname.cpp will contain the static definitions and remaining meth- ods.

The final application would be written in Application.cpp (or some such file – to be documented in README). There may be more than one application file for testing.

Positive and negative test files may be separate.

Test Plan

</div>
</div>
<div class="layoutArea">
<div class="column">
We also need to prepare a test plan to test the implementation at different stages of development so that better quality and productivity can be ensured. Variety of test processes are common. We shall follow two of these in the current assignment.

</div>
</div>
<div class="layoutArea">
<div class="column">
23

</div>
</div>
</div>
<div class="page" title="Page 24">
<div class="layoutArea">
<div class="column">
6.1 Unit Tests

This is typically the basic test process which is engaged during development (however, it may be useful for future testing and debugging as well). In this, we test every class as it is implemented. We test all non-static &amp; static member functions and friend functions. For a class hierarchy, the unit test is done typically at both concrete classes and the overall hierarchy levels specifically checking the polymorphic methods.

For the purpose of understanding, in Section ?? we illustrate the test plan and test function for a few unit cases for the Fraction class we have developed in Assignment 2.

6.2 Application Test

After the units have been tested, we integrate them into the application and test various scenarios for the application. A sample test application was provided for the Fraction class in Assignment 2. However, since it was just a single class application, the application code looked pretty much like the unit test application code with the exception of the comparison with golden data.

Like the units, we again need to enumerate scenarios for the application in the test plan and write the applica- tion test.

In addition, a sample test application for booking is given in Section ?? with the expected output in Section ??. Your codes should pass this test application too.

7 Tasks

7.1 Assignment 4: UML Diagrams: Analysis &amp; Design Phases

The following tasks are to be completed for the assignment:

1. UML Diagrams: Study the specifications of the booking system, and the analyses &amp; design as discussed

above to prepare the final analysis cum design document UML.pdf with the following Diagrams:

• Use Case Diagram: Identify the actors, use-cases &amp; relationships.

• Class Diagram: Show the classes (with properties &amp; operations), relationships &amp; associations. • Sequence Diagram: Depict the lifelines, messages &amp; interaction fragments.

• Communication Diagram: Depict the frames, lifelines &amp; messages.

• Activity Diagram: Model the activities, edges, controls, objects &amp; actions.

• State Chart Diagram: Appropriately define the state machine for the problem.

• Note:

<ul>
<li>– &nbsp;Use annotations liberally in the diagrams as needed. Add more notes in the document to explain the diagrams as appropriate.</li>
<li>– &nbsp;Some UML tools like Visual Paradigm Online may used to generate the diagrams</li>
<li>– &nbsp;You need to model handling of errors wherever needed, however, do not model exceptions as theseare specific to C++.
2. Analysis &amp; Design: Complete the HLD and the LLD in C++. Document the salient points from your design in Design.txt / Design.pdf. Follow the quality guidelines and design principles outlined above.

• Note:

<ul>
<li>– &nbsp;Necessary parts of HLD and all of LLD should be for C++.</li>
<li>– &nbsp;Design of every class (and hierarchy) should detail the non-static &amp; static data members, non-static &amp; static methods with const-ness and polymorphism as applicable.</li>
<li>– &nbsp;Details of methods (algorithm) may be skipped – only interface would suffice.</li>
<li>– &nbsp;Exceptions should be modeled.3. Bundle and Submissions: Name and bundle your files as given in Section 8 and submit to Moodle.</li>
</ul>
</li>
</ul>
</div>
</div>
<div class="layoutArea">
<div class="column">
24

</div>
</div>
</div>
<div class="page" title="Page 25">
<div class="layoutArea">
<div class="column">
7.2 Assignment 5: Test Plan, Implementation &amp; Test Report

The following tasks are to be completed for the assignment:

</div>
</div>
<div class="layoutArea">
<div class="column">
1. 2.

3.

4.

8

8.1

</div>
<div class="column">
Implementation: Implement the LLD in C++ following the basic coding guidelines (Section A).

Test Planning: Write a unit test and application test plan in Testplan.txt covering all scenarios. Also, write the test suite with a couple of test cases for every scenario and golden output. Note that all wrong input or erroneous data situations are to be handled. Hence, the test plan and suite must cover positive and negative tests both.

Testing &amp; Test Report: Implement unit test and application test codes and perform testing. Based on the test plan and suite, generate the PASS/FAIL report.

Bundle and Submissions: Name and bundle your files as given in Section 8 and submit to Moodle. Submission of Files

Assignment 4: UML Diagrams: Analysis &amp; Design Phases

</div>
</div>
<div class="layoutArea">
<div class="column">
The following files must be submitted as a single ZIP file:

<ol>
<li>UML.pdf: Use Case, Class and Sequence, Communication, Activity &amp; State Machine Diagrams, annota- tions, notes.</li>
<li>Design.txt / Design.pdf: The design document stating the design details (especially LLD) with princi- ples and guidelines followed</li>
</ol>
Every file must have your name and roll number.

8.2 Assignment 5: Test Plan, Implementation &amp; Test Report

The following files must be submitted as a single ZIP file: 1. Documents.zip

<ol>
<li>(a) &nbsp;Testplan.txt / Testplan.pdf: The test plan document stating scenarios for unit tests and of the test application, and test cases (with golden output).</li>
<li>(b) &nbsp;Testreport.txt / Testreport.pdf: The test report document based on the test plan and suite showing PASS / FAIL of test cases.</li>
</ol>
2. Source.zip:

<ol>
<li>(a) &nbsp;Source (.cpp) and header (.h) files for classes.</li>
<li>(b) &nbsp;Source (.cpp) and header (.h) files for test applications.</li>
<li>(c) &nbsp;README file that describes the contents of every file in the Source.zip. Also, mention the compiler (with version, and compiler options, if any) that you have used.</li>
</ol>
3. Outputs.zip

(a) Output from the your test application developed from the test plans

• The output file can be generated by redirecting the output to a text file or by copy-paste from the console in a text file.

• There is no need to include the a.out file.

(b) Both positive as well as negative outputs must be shown.

Every file (with the exception of program output) must have your name and roll number.

</div>
</div>
<div class="layoutArea">
<div class="column">
25

</div>
</div>
</div>
<div class="page" title="Page 26">
<div class="layoutArea">
<div class="column">
9 Marks

9.1 Assignment 4: UML Diagrams: Analysis &amp; Design Phases

</div>
</div>
<div class="layoutArea">
<div class="column">
The marks are distributed as follows:

UML

</div>
<div class="column">
[60]

[40]

</div>
</div>
<div class="layoutArea">
<div class="column">
The marks are distributed as follows:

Implementation

Happy Paths Exceptional Paths

Test Planning

</div>
<div class="column">
Breakup

Breakup

</div>
<div class="column">
[25] [15]

[10] [5] [15]

[7] [3]

[2] [2] [6] [5] [5]

</div>
<div class="column">
[40]

[30]

[10]

[20]

</div>
</div>
<div class="layoutArea">
<div class="column">
Use Case Diagram

Class Diagram

Sequence Diagram Communication Diagram Activity Diagram

</div>
<div class="column">
[5] [20] [10] [5] [15] [5]

[4] [4] [5] [3] [3] [5] [5] [8] [3]

</div>
</div>
<div class="layoutArea">
<div class="column">
State Machine Diagram

Design

</div>
</div>
<div class="layoutArea">
<div class="column">
Design of Station &amp; Railways Classes

Design of Date Class

Design of BookingClass Class &amp; Hierarchy Design of Divyaang Class &amp; Hierarchy

Design of Concessions Class &amp; Hierarchy Design of BookingCategory Class &amp; Hierarchy Design of Passenger Class &amp; Hierarchy

Design of Booking Class &amp; Hierarchy Design of Exceptions Class &amp; Hierarchy

</div>
</div>
<div class="layoutArea">
<div class="column">
9.2 Assignment 5: Test Plan, Implementation &amp; Test Report

</div>
</div>
<div class="layoutArea">
<div class="column">
Unit Test Scenarios Application Test Scenarios Test Cases &amp; Goldens

Testing &amp; Test Report

Breakup

Unit Test Report Application Test Report

Quality of Design &amp; Implementation

Breakup

Adherence to Design Protocols Singletons

const-ness Sub-Typing Coding Guidelines

Code Comments

</div>
</div>
<div class="layoutArea">
<div class="column">
Breakup

</div>
</div>
<div class="layoutArea">
<div class="column">
Breakup

</div>
</div>
<div class="layoutArea">
<div class="column">
26

</div>
</div>
</div>
<div class="page" title="Page 27">
<div class="layoutArea">
<div class="column">
A Coding Guidelines

It is advised to follow the guidelines below while coding:

• Use CamelCase for naming variables, classes, types and functions

• Every name should be indicative of its semantics

• Start every variable with a lower case letter

• Start every function and class with an upper case letter

• Use a trailing underscore ( ) for every non-static data member

• Use a leading ’s’ for every static data member

• Do not use any global variable or function (except main(), and friends)

• No constant value should be written within the code – should be put in the application as static • Prefer to pass parameters by value for build-in type and by const reference for UDT

• Every polymorphic hierarchy must provide a virtual destructor in the base class

• *Constructors and destructors should never throw

• *Virtual functions should not be called in constructors of base classes

• Prefer C++ style casting (like static cast&lt;int&gt;(x) over C Style casting (like (int))

• The project should compile without any compiler warning

• Indent code properly

• Comment the code liberally and meaningfully

• Adopt more guidelines as you prefer. Try to document them

B Clarifications

It may be noted that analyses (Section 2) and designs (Section 3, and Section 4) as discussed are indicative. These are provided to get you started and to show how the specification may map to the design styles as we have discussed in C++. However, they are not binding. Many of you are coming up with alternate design proposals and asking for approval. It is okay that you make your own choice if you feel more comfortable to think in that manner. Just explain the choice clearly in the design document.

B.1 Queries

B.1.1 Deep Majumder

I have some doubts regarding the new Assignment.

1. It has been mentioned in the assignment that BookingClass can be reduced to a flat hierarchy. But what is the necessity of an explicit hierarchy at all? Combining anonymous namespaces and Factory patterns gives us a way to have Singletons for each booking class. Moreover, this falls in nicely with a Singleton Config manager, which contains master data read from a file. By not having a explicit (flat) hierarchy, we can get rid of a lot of code, possibly even duplicated ones. And also relieves us of explicitly initializing a lot of static constant members (7 * 8 = 56 in for Booking Classes). So is this an acceptable way to model BookingClass? Or is the hierarchy necessary?

PPD: Hierarchy is not a must, just an advise. Since this will need to be done for other class hierarchies, BookingClass may also be fit into the same template style.

Further, I wanted people to first master writing templates, and on hierarchy, without using other existing solution. Without a lot of discussions, it would not be easy for most to handle the solution in the way you are suggesting. However, you are free to use any style you prefer.

Finally, I have two observations on your comments – (1) With inclusion-parametric flat hierarchy, I do not think code bloats or there is need to write duplicate codes. I tried that out. Of course, I would be interested to check your solution for better options. (2) I am not sure how we can avoid the initialization of the constants. They need to be put anyway. May be I am missing something. Will look forward to what you do.

</div>
</div>
<div class="layoutArea">
<div class="column">
27

</div>
</div>
</div>
<div class="page" title="Page 28">
<div class="layoutArea">
<div class="column">
<ol start="2">
<li>It has been said that the master data can be read from input files and need not be hardcoded. I plan to use some structured format like YAML, or JSON, or XML. Do I need to provide a schema as well or can I implicitly assume the data format?PPD: This is optional. You may read it from a file if you want. You can choose any schema or your own format if you decide to do it.</li>
<li>Reading master data from a file I think introduces a problem with Singletons. In C++, all static member initialization is done before main is executed. As a result, the config file location cannot be passed from main (command line args or otherwise). So it must be hardcoded. But since C++ doesn’t guarantee the order in which static variables are initialized, the filename cannot be stored in a string (or even C-string), because we do not know whether it is initialized or uninitialized (we will have an unreliable design). So the filename must be hardcoded as a string literal. To avoid repeating we have to use a macro (red-flags, I know). Is there a better way out?PPD: Very interesting question and observation. You have rightly pointed out a tricky situation in terms of global static objects and their initialization (one of the reasons I prefer local static objects whenever possible).
The problem of passing the file name can be addressed if we assume to read it from the stdin which can work even before main() starts (don’t ask how stdin gets initialized and when). This reading of the file name must happen before the first initialization data is needed (and before main() starts). That can be done (check Approach 2 below).

In fact, besides the input file name, there is a deeper problem. The file is a serial structure. It will contain the initialization values in a certain order. And the global static values will be initialized in an unknown order, requiring values coming from the input file. How do we guarantee their alignment?

Here, I shall present three approaches – based on the following three philosophy:

<ul>
<li>Approach 1: Do not initialize. Set to default. Set values after main starts.</li>
<li>Approach 2: Have a singleton to collect all values from input file (this can be done before the first initialization). Then the accumulated values are set for initialization in whatever order they happen.</li>
<li>Approach 3: Do not use global static data member. Use only local static data with static methods. Think, as if, every static data member is a singleton.Of course, there could be more. And none of them is perfect. Let me now explain.
Approach 1: The singletons in the project can use the Meyer’s version where they would be local static objects and hence will be constructed only on first use (naturally after main() starts), not before main(). So we do not need to be concerned about them.

The static data in this project are all of built-in type (having no constructor). So they can be defaulted to 0 (for int) or 0.0 (for double) or “” (for string) or true (for bool) in the code. Of course, this leads to a problem – the static objects cannot be const any more. That may not be a major issue because all these are private in the respective classes, but raises the question of how does main() can access and set them with the values read from the file. The solution would be to have a InitStatic class which does the job and can be friend of all necessary classes. Quite a mess.

Also note that this approach will not work if the static data member is a UDT and does not have a default constructor.

Approach 2: If you abhor the rampant use of friend (I do), we can follow a different scheme. We can have a singleton SetStatic class which reads the static values from the input file during its construction and puts in its data members. So all static initialization will get the value through this singleton object which actually reads the data from the input file. This solves the problem that static data can be initialized in arbitrary order. No matter which order it happens, the first access to static will create this singleton and read the file. A sample code files is given below.

There are four files:
</li>
</ul>
<ul>
<li>MyClass.h: This has an abstract base class MyClass with two sub-classes MyClass::MyType1 and MyClass::MyType2 in the emulation of a minimal inclusion-parametric polymorphism (that we are widely using in the design). Each sub-type has four static data members of int, double, string and bool types to show how to set their initial values. This is for the purpose of illustration.</li>
<li>MyClass.cpp: This file defines the static data members of both sub-types. There is a commented code where these are initialized directly. In the other part they are emulated to have been read from the input file using the SetStatics class.</li>
</ul>
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
28

</div>
</div>
</div>
<div class="page" title="Page 29">
<div class="layoutArea">
<div class="column">
• SetStatics.h: This is singleton class which is designed with data members as proxy of the static data members of each sub-type above. These are named explicitly for identification without class scopes (this is not good, but works – think about a better solution). The data members are non-const as they have to be set from reading the file. They are made private and endowed with corresponding Get methods (this actually is redundant as these values would not be used after the initialization – still following the usual OOP paradigm). Note that actual reading from file is not shown for simplicity.

• App.cpp: This illustrates the use of the sub-type objects with dynamic dispatch.

// MyClass.h

<pre>#ifndef __MY_CLASS_H
#define __MY_CLASS_H
</pre>
<pre>// ***** MyClass class &amp; hierarchy definition
// ***** Author: P P Das
// ***** Date: 23-Mar-2021
// ***** Version: 1.0
</pre>
<pre>// ***** Known bugs: None
</pre>
<pre>// ***** C++ Standard Library Headers
#include &lt;iostream&gt;
#include &lt;string&gt;
using namespace std;
</pre>
<pre>// Forward declaration of templatized class
template&lt;class T&gt;
class MyClassType;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// Generic BookingCategory type
class MyClass { // Abstract Base Class
</pre>
<pre>    // Tag types
    struct Type1 { };
    struct Type2 { };
</pre>
<pre>protected:
    MyClass() { }
</pre>
<pre>    virtual ~MyClass() = 0;
</pre>
<pre>public:
    virtual void Print() const = 0;
</pre>
<pre>    // Enumerated types
    typedef MyClassType&lt;Type1&gt; MyType1;
    typedef MyClassType&lt;Type2&gt; MyType2;
</pre>
<pre>};
inline MyClass::~MyClass() {}
</pre>
<pre>// Specific MyClass types
template&lt;class T&gt;
class MyClassType : public MyClass {
</pre>
<pre>    static const string sName;
    static const int sAge;
    static const double sSalary;
    static const bool sIsMale;
</pre>
<pre>    MyClassType() : MyClass() { }
</pre>
<pre>    ~MyClassType() { }
public:
</pre>
</div>
<div class="column">
<pre>// Name of the person
// Age of the person
// Salary of the person in Rs. Lakhs
// Gender of the person
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// Singleton object - placeholder for the respective type
static const MyClassType&amp; Type() {
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
29

</div>
</div>
</div>
<div class="page" title="Page 30">
<div class="layoutArea">
<div class="column">
<pre>static MyClassType theObject;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>        return theObject;
    }
</pre>
<pre>    void Print() const;
};
</pre>
<pre>// Print methods
inline void MyClass::MyType1::Print() const {
</pre>
<pre>    cout &lt;&lt; "Printing a MyType1 Object" &lt;&lt; endl;
    cout &lt;&lt; "Name = " &lt;&lt; sName &lt;&lt; endl;
    cout &lt;&lt; "Age = " &lt;&lt; sAge &lt;&lt; " years" &lt;&lt; endl;
    cout &lt;&lt; "Salary = Rs. " &lt;&lt; sSalary &lt;&lt; " lakhs" &lt;&lt; endl;
    cout &lt;&lt; "Gender = " &lt;&lt; ((sIsMale)? "Male": "Female") &lt;&lt; endl;
</pre>
return; }

<pre>inline void MyClass::MyType2::Print() const {
    cout &lt;&lt; "Printing a MyType2 Object" &lt;&lt; endl;
    cout &lt;&lt; "Name = " &lt;&lt; sName &lt;&lt; endl;
    cout &lt;&lt; "Age = " &lt;&lt; sAge &lt;&lt; " years" &lt;&lt; endl;
    cout &lt;&lt; "Salary = Rs. " &lt;&lt; sSalary &lt;&lt; " lakhs" &lt;&lt; endl;
    cout &lt;&lt; "Gender = " &lt;&lt; ((sIsMale) ? "Male" : "Female") &lt;&lt; endl;
</pre>
return; }

<pre>#endif // __MY_CLASS_H
</pre>
<pre>// MyClass.cpp
</pre>
<pre>// ***** MyClass class &amp; hierarchy definition
// ***** Author: P P Das
// ***** Date: 23-Mar-2021
// ***** Version: 1.0
</pre>
<pre>// ***** Known bugs: None
</pre>
<pre>// ***** C++ Standard Library Headers
#include &lt;iostream&gt;
#include &lt;string&gt;
using namespace std;
</pre>
<pre>// ***** Project Headers
#include "SetStatics.h"
#include "MyClass.h"
</pre>
<pre>// Model for reading from a file through a singleton
const string MyClass::MyType1::sName = SetStatics::Static().GetMyClass_MyType1_sName();
const int MyClass::MyType1::sAge = SetStatics::Static().GetMyClass_MyType1_sAge();
const double MyClass::MyType1::sSalary = SetStatics::Static().GetMyClass_MyType1_sSalary();
const bool MyClass::MyType1::sIsMale = SetStatics::Static().GetMyClass_MyType1_sIsMale();
</pre>
<pre>const string MyClass::MyType2::sName = SetStatics::Static().GetMyClass_MyType2_sName();
const int MyClass::MyType2::sAge = SetStatics::Static().GetMyClass_MyType2_sAge();
const double MyClass::MyType2::sSalary = SetStatics::Static().GetMyClass_MyType2_sSalary();
const bool MyClass::MyType2::sIsMale = SetStatics::Static().GetMyClass_MyType2_sIsMale();
</pre>
<pre>// Setting static values directly
//const string MyClass::MyType1::sName = "Ravi Narayan";
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
30

</div>
</div>
</div>
<div class="page" title="Page 31">
<div class="layoutArea">
<div class="column">
<pre>//const int MyClass::MyType1::sAge = 40;
//const double MyClass::MyType1::sSalary = 10.75;
//const bool MyClass::MyType1::sIsMale = true;
//
//const string MyClass::MyType2::sName = "Pratibha Kannan";
//const int MyClass::MyType2::sAge = 37;
//const double MyClass::MyType2::sSalary = 15.30;
//const bool MyClass::MyType2::sIsMale = false;
</pre>
<pre>// SetStatics.h
</pre>
<pre>#ifndef __SET_STATICS_H
#define __SET_STATICS_H
</pre>
<pre>// ***** SetStatics class
// ***** Author: P P Das
// ***** Date: 23-Mar-2021
// ***** Version: 1.0
</pre>
<pre>// ***** Known bugs: None
</pre>
<pre>// ***** C++ Standard Library Headers
#include &lt;string&gt;
using namespace std;
</pre>
<pre>// ***** Project Headers
#include "MyClass.h"
</pre>
<pre>class SetStatics {
    // Proxy data members for static values
    string MyClass_MyType1_sName;
    int MyClass_MyType1_sAge;
    double MyClass_MyType1_sSalary;
    bool MyClass_MyType1_sIsMale;
</pre>
<pre>    string MyClass_MyType2_sName;
    int MyClass_MyType2_sAge;
    double MyClass_MyType2_sSalary;
    bool MyClass_MyType2_sIsMale;
</pre>
<pre>    SetStatics() {
        // Read the input file name from stdin - not shown
</pre>
<pre>        // Open the input file - not shown
</pre>
<pre>        // These values are read from the input file
        // This happens only once
        MyClass_MyType1_sName = "Ravi Narayan";
        MyClass_MyType1_sAge = 40;
        MyClass_MyType1_sSalary = 10.75;
        MyClass_MyType1_sIsMale = true;
</pre>
<pre>        MyClass_MyType2_sName = "Pratibha Kannan";
        MyClass_MyType2_sAge = 37;
        MyClass_MyType2_sSalary = 15.30;
        MyClass_MyType2_sIsMale = false;
</pre>
}

<pre>public:
    static const SetStatics&amp; Static() {
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>static SetStatics theObject;
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
31

</div>
</div>
</div>
<div class="page" title="Page 32">
<div class="layoutArea">
<div class="column">
<pre>        return theObject;
    }
</pre>
<pre>    // Get methods for the static values we need to set
    const string&amp; GetMyClass_MyType1_sName() const { return MyClass_MyType1_sName; }
    const int GetMyClass_MyType1_sAge() const { return MyClass_MyType1_sAge; }
    const double GetMyClass_MyType1_sSalary() const { return MyClass_MyType1_sSalary; }
    const bool GetMyClass_MyType1_sIsMale() const { return MyClass_MyType1_sIsMale; }
</pre>
<pre>    const string&amp; GetMyClass_MyType2_sName() const { return MyClass_MyType2_sName; }
    const int GetMyClass_MyType2_sAge() const { return MyClass_MyType2_sAge; }
    const double GetMyClass_MyType2_sSalary() const { return MyClass_MyType2_sSalary; }
    const bool GetMyClass_MyType2_sIsMale() const { return MyClass_MyType2_sIsMale; }
</pre>
<pre>};
#endif // __SET_STATICS_H
</pre>
// App.cpp

<pre>// ***** MyClass Application
// ***** Author: P P Das
// ***** Date: 23-Mar-2021
// ***** Version: 1.0
</pre>
<pre>// ***** Known bugs: None
</pre>
<pre>// ***** C++ Standard Library Headers
#include &lt;iostream&gt;
#include &lt;string&gt;
using namespace std;
</pre>
<pre>// ***** Project Headers
#include "MyClass.h"
</pre>
<pre>int main() {
    const MyClass&amp; r1 = MyClass::MyType1::Type();
    const MyClass&amp; r2 = MyClass::MyType2::Type();
</pre>
<pre>    cout &lt;&lt; endl;
    r1.Print();
</pre>
<pre>    cout &lt;&lt; endl;
    r2.Print();
</pre>
return 0; }

Approach 3: Another way could be to not use global static data members at all. Instead, we could make all of them as local static data and replace them by global static methods in the respective class. Then their initialization comes under the control of the program after main(). So it can be managed in the order the application wants. Of course, that itself, may become a big issue as the file that provides the data is a serial structure and the order in which we want to initialize the objects may not be aligned with that order – or at least be difficult to align. The work around that would be to use separate input file for each class – but then, we would need to read the name of the file and map with the class. That too is not clean.

Now the four files will be as follows:

• MyClass.h: Changes static data members from global objects to static methods with local static data. This is given below.

</div>
</div>
<div class="layoutArea">
<div class="column">
32

</div>
</div>
</div>
<div class="page" title="Page 33">
<div class="layoutArea">
<div class="column">
• MyClass.cpp: Definitions of static data members are omitted. This is given below.

This file may be skipped too as MyClass.h has every method as inline and will get compiled as a part of App.cpp

• SetStatics.h: Not needed.

• App.cpp: No change except excluding SetStatics.h from inclusion.

// MyClass.h

<pre>#ifndef __MY_CLASS_H
#define __MY_CLASS_H
</pre>
<pre>// ***** MyClass class &amp; hierarchy definition
// ***** Author: P P Das
// ***** Date: 23-Mar-2021
// ***** Version: 1.0
</pre>
<pre>// ***** Known bugs: None
</pre>
<pre>// ***** C++ Standard Library Headers
#include &lt;iostream&gt;
#include &lt;string&gt;
using namespace std;
</pre>
<pre>// Forward declaration of templatized class
template&lt;class T&gt;
class MyClassType;
</pre>
<pre>// Generic BookingCategory type
class MyClass { // Abstract Base Class
</pre>
<pre>    // Tag types
    struct Type1 { };
    struct Type2 { };
</pre>
<pre>protected:
    MyClass() { }
</pre>
<pre>    virtual ~MyClass() = 0;
</pre>
<pre>public:
    virtual void Print() const = 0;
</pre>
<pre>    // Enumerated types
    typedef MyClassType&lt;Type1&gt; MyType1;
    typedef MyClassType&lt;Type2&gt; MyType2;
</pre>
<pre>};
inline MyClass::~MyClass() {}
</pre>
<pre>// Specific MyClass types
template&lt;class T&gt;
class MyClassType : public MyClass {
</pre>
<pre>    MyClassType() : MyClass() { }
</pre>
<pre>    ~MyClassType() { }
public:
</pre>
<pre>    // Singleton object - placeholder for the respective type
    static const MyClassType&amp; Type() {
</pre>
<pre>        static MyClassType theObject;
</pre>
<pre>        return theObject;
    }
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// Name of the person
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
33

</div>
</div>
</div>
<div class="page" title="Page 34">
<div class="layoutArea">
<div class="column">
<pre>static const string&amp; GetName();
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>    // Age of the person
    static const int GetAge();
</pre>
<pre>    // Salary of the person in Rs. Lakhs
    static const double GetSalary();
</pre>
<pre>    // Gender of the person
    static const bool IsMale();
</pre>
<pre>    void Print() const;
};
</pre>
<pre>// Name of the person
inline const string&amp; MyClass::MyType1::GetName() {
</pre>
<pre>    static const string sName = "Ravi Narayan"; // Read from file
</pre>
<pre>    return sName;
}
</pre>
<pre>// Age of the person
inline const int MyClass::MyType1::GetAge() {
</pre>
<pre>    static const int sAge = 40; // Read from file
</pre>
<pre>    return sAge;
}
</pre>
<pre>// Salary of the person in Rs. Lakhs
inline const double MyClass::MyType1::GetSalary() {
</pre>
<pre>    static const double sSalary = 10.75; // Read from file
</pre>
<pre>    return sSalary;
}
</pre>
<pre>// Gender of the person
inline const bool MyClass::MyType1::IsMale() {
</pre>
<pre>    static const bool sIsMale = true; // Read from file
</pre>
<pre>    return sIsMale;
}
</pre>
<pre>// Print methods
inline void MyClass::MyType1::Print() const {
</pre>
<pre>    cout &lt;&lt; "Printing a MyType1 Object" &lt;&lt; endl;
    cout &lt;&lt; "Name = " &lt;&lt; GetName() &lt;&lt; endl;
    cout &lt;&lt; "Age = " &lt;&lt; GetAge() &lt;&lt; " years" &lt;&lt; endl;
    cout &lt;&lt; "Salary = Rs. " &lt;&lt; GetSalary() &lt;&lt; " lakhs" &lt;&lt; endl;
    cout &lt;&lt; "Gender = " &lt;&lt; ((IsMale())? "Male": "Female") &lt;&lt; endl;
</pre>
return; }

<pre>// Name of the person
inline const string&amp; MyClass::MyType2::GetName() {
</pre>
<pre>    static const string sName = "Pratibha Kannan"; // Read from file
</pre>
<pre>    return sName;
}
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
<pre>// Age of the person
</pre>
</div>
</div>
<div class="layoutArea">
<div class="column">
34

</div>
</div>
</div>
<div class="page" title="Page 35">
<div class="layoutArea">
<div class="column">
<pre>     inline const int MyClass::MyType2::GetAge() {
         static const int sAge = 37; // Read from file
</pre>
<pre>         return sAge;
     }
</pre>
<pre>     // Salary of the person in Rs. Lakhs
     inline const double MyClass::MyType2::GetSalary() {
</pre>
<pre>         static const double sSalary = 15.30; // Read from file
</pre>
<pre>         return sSalary;
     }
</pre>
<pre>     // Gender of the person
     inline const bool MyClass::MyType2::IsMale() {
</pre>
<pre>         static const bool sIsMale = false; // Read from file
</pre>
<pre>         return sIsMale;
     }
</pre>
<pre>     inline void MyClass::MyType2::Print() const {
         cout &lt;&lt; "Printing a MyType2 Object" &lt;&lt; endl;
         cout &lt;&lt; "Name = " &lt;&lt; GetName() &lt;&lt; endl;
         cout &lt;&lt; "Age = " &lt;&lt; GetAge() &lt;&lt; " years" &lt;&lt; endl;
         cout &lt;&lt; "Salary = Rs. " &lt;&lt; GetSalary() &lt;&lt; " lakhs" &lt;&lt; endl;
         cout &lt;&lt; "Gender = " &lt;&lt; ((IsMale()) ? "Male" : "Female") &lt;&lt; endl;
</pre>
return; }

<pre>     #endif // __MY_CLASS_H
</pre>
<pre>     // MyClass.cpp
</pre>
<pre>     // ***** Project Headers
     #include "MyClass.h"
</pre>
So to conclude Approach 2 seems to be the best option till we find a better solution. It is a bit of coding but is clean and less error-prone. However, I am still concerned with the fact that nice scoped names like MyClass::MyType1::sName have to be encoded in terms of synthetic names like MyClass MyType1 sName and GetMyClass MyType1 sName() – leaving a huge possibility of manual error. Let us keep looking for a better solution.

4. Since using double-dispatch for object construction (the ”virtual” constructor idiom) tightly couples classes, aren’t we better off simply using the Factory pattern? The double dispatch trick works well with Visitors, but I wonder how useful it is for object construction.

PPD: You are right. I shall try to discuss this more if I get time to talk on various design patterns. For now, it will be too much to expect this from you all without having discussed them in the class.

B.1.2 Kunal Singh

1. Sir in assignment 4 in the use case diagram i am only able to identify passenger as an actor and his only use case being initiation of booking which then includes / extends other dependent use cases could you help me out please ?

PPD: In Use-case it is not necessary that all actors be modeled in the final software. For example, we can think of the booking executive who does the booking. The same person who does intends to travel as a passenger may be the booking executive. But he is a different actor. Then the booking needs to be printed out. We need printer actor. A database is needed to keep the booking records. A booking manager is an actor who sets the static data like station names and distances. Etc. These are the use-case views. When

</div>
</div>
<div class="layoutArea">
<div class="column">
35

</div>
</div>
</div>
<div class="page" title="Page 36">
<div class="layoutArea">
<div class="column">
you come to later diagrams in later stages, you may want to merge some of them or skip their explicit existence. Use case is about actors and actions. That must truly visualized.

2. sir I’ve come up with the following design of booking category actually I got confused with the clarification mail , is this design appropriate ? sorry to bother you again.

PPD: There could be multiple ways to model. And you have your choice. Yes, you may visualize in this way. However, this is the hierarchy for BookingCategory, not for BookingClass (which is information on First Class, AC Tier 2, etc.).

B.1.3 Nakul Aggarwal

1. Page No. 22 (highlighted in yellow) (important)

</div>
</div>
<div class="layoutArea">
<div class="column">
36

</div>
</div>
</div>
<div class="page" title="Page 37">
<div class="layoutArea">
<div class="column">
Does this mean that in all the classes where there is a scope of attempting construction with wrongly formatted or invalid inputs, we should make the constructor private and use a static method at its place in the public? (like we do for singleton classes – there we need to preserve the number of calls to the constructor, here we need to preserve the validity of the inputs passed to the constructor)

PPD: You are right. We use a static method to check the validity of the input and then construct, and finally return the object. With this, we do not need to throw from a constructor, which may leave us in an inconsistent object state.

For example, while constructing a Passenger class object, we have to make sure various input validity like dob, aadhaar, mobile etc. hold and constraints on name can be ensured. So we can have a static method CreatePassenger that does the checking, throws appropriately on errors, and then constructor the Passenger object if everything in fine. In some case, like for Railways, this may get a little tricky because you have to decide on the interplay between the singleton static method and the value checking static method. Note that for the singleton static method, it is okay to throw an exception because it is not a constructor.

You would not to do such idioms for constructing objects for classes where no input data validation is necessary, like BookingClass or Concessions. They depend on pre-validated static data only.

<ol start="2">
<li>Relevance of Virtual Construction Idiom in Ad-Hoc Polymorphic Hierarchy Sir, the Concessions class that is rooted at the BookingCategory class realises ad-hoc polymorphism. In this case, how can it perform dynamic dispatch that is required in the ”virtual construction”? Secondly, I am confused with the proposed model of BookingCategory hierarchy. For Concessions hierarchy ad-hoc polymorphism is used. While for Divyaang and PriorityCategories hiearchies, inclusion-parametric polymorphism is used. Both the hierarchies are rooted at BookingCategory class (that might be abstract). Does this mean that among some of the derived classes we are allowing dynamic dispatch and among others we are not? Why can’t we use inclusion polymorphism at the place of ad-hoc? Will virtual construction idiom work with such a ”half ad-hoc half inclusion-parametric hierarchy”?PPD: You are getting confused between three things – parametric polymorphism, inclusion polymorphism and virtual construction idiom. Let us look at them one by one.
First, there are a number of hierarchies here – each rooted at its respective root class (which may be abstract). These include BookingClass, Concessions etc. They are rooted separately – NOT at Booking- Category.

Second, let us see when parametric polymorphism is useful. Using templates, we write a generic code, that instantiates to a number of specific codes based on the type. So the methods of these instantiated classes need to be “parameterizable” – by the values they use and the types they engage. Simply widely different algortihms for different overloads (overrides) of a method would not be a good candidate for parametric polymorphism. Rather, we should use inclusion polymorphism and code every algorithm for every class separately. This is what Concessions warrant because in some cases we do not give concession at all, in some we depend on gender or gender &amp; age, and in others we use the disability information. They are not parametrically combinable. Typically, when we have a flat one level hierarchy, we can use parametric polymorphism for the leaf classes and an abstract base class to provide a uniform interface with dynamic dispatch. That is the case for many class hierarchies here.

Finally, virtual construction becomes necessary when we the particular type of object that we have to construct for a hierarchy (PoolSlot in Section 3.2.2) depends on the type of another object from a different hierarchy (Gender). In our specific context, Booking would be a hierarchy because the fare computation logic depends on the BookingCategory. How do we create an appropriate Booking object then given a specific BookingCategory (and BookingClass)? I hope this clarifies.
</li>
<li>UML Diagrams Is it totally upto us to decide the level of abstraction of the diagrams? We have seen many class diagrams in the class that have no attributes/operations written in them; only generaliza- tion, aggregation etc relationships are used to design these diagrams. So is it fine if we omit some attributes/operations? I am asking this because here we have a lot of classes; this might clutter the diagram a lot if attributes and operations are written for each one of them.PPD: Of course, it is your choice. However, it is necessary to chose appropriate abstraction (not only limited to properties and methods, there are associations, relationships, message for Sequence etc.) so that all design considerations and details and available “only” from the diagrams. The class diagram in the solution of Assignment 3 could serve as a sample.
We have shown several examples to handle clutter. In one diagram a class may be detailed, in others it may just come in by name. You need to make an appropriate choice.
</li>
</ol>
</div>
</div>
<div class="layoutArea">
<div class="column">
37

</div>
</div>
</div>
<div class="page" title="Page 38">
<div class="layoutArea">
<div class="column">
B.1.4 Parth Jindal

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>This is in regards to the 4th assignment for CS21006. In the Error and Exceptions, It was written in he Passenger section that ”gender must be male or female. It must be valid by input” Does this imply that it is assumed that the input is given by the user from a ’drop-down menu’ hence there may not be any need to validate it just like for BookingClass and BookingCategory (by validation I mean if ”it is out of category”) or we should still validate it.PPD: You are right. The passenger chooses the Gender from a drop-down (like she / he does for Book- ingClass or BookingCategory). That process can be emulated by our system by using appropriate Gender or other types in the request. Naturally, these inputs do not need validation – in a GUI system no invalid input can be given for these, and in our system the code will not compile if we provide a wrong type. So, for example, we cannot allow to input a string like “male” for Gender because it is always possible to misspell it as “meal” and the compiler will not give an error (but our runtime system will fail). Hence, it is important these as type constant as explained above.</li>
<li>Another question I had in mind was the role of disabilityID in determining the eligibility for Divyaang BookingCategory booking and its validation?PPD: disabilityID does not need validation because it can come from various agencies and is not reg- ulated to be in a certain format (like aadhaar is). It is more a representative for a certificate that the passenger would need to upload for a GUI based system.
The type of Divyaang is assumed to be from a drop-down in a GUI and will be emulated by type constant so that it cannot be wrong. The BookingCategory details will be validated against it and the fare will be computed by the corresponding business logic. So, Divyaang category of booking can be allowed for Divyaang type passenger only (and the fare will be based on the type of disability and the BookingClass), while General or other category of booking will be allowed for a Divyaang passenger if she / he has sought for it and qualifies.
</li>
</ol>
B.1.5 Rohan Raj

<ol>
<li>In passenger data type, there are many optional attributes. Creating different functions for all of the cases would be time consuming and not that much important. I have an alternative. If A person don’t have a first name, we can pass empty string as the argument. Same goes for all the optional arguments. Can we do that?PPD: It would be a design choice for you.</li>
<li>While validating passenger object, do we have to consider date of reservation to calculate the age or thedate extracted from the library(current date) ?
PPD: You need both – the date on which the booking is done (today from the library) and the date of travel. There are validations on both.
</li>
</ol>
B.1.6 Shrinivas Khiste

1. I am having trouble understanding how to implement ad-hoc polymorphism. On the internet, it says that it involves function overloading. Then how is it defined for a class and have a hierarchy? If we use the function overloading definition then we can define different functions to calculate concessions for each type. But how do we implement it for the Exception Classes?

PPD: Ad-hoc polymorphism is function overloading. Correct. It may be between global functions, member functions of the same class, or member function of one class and its parent in a hierarchy. It is the simple static form of polymorphism and must differ in the signature between two polymorphic forms. We have discussed all these cases in the class.

While ad-hoc polymorphism is possible on an inheritance hierarchy, most often it is not interesting and / or useful. What we need there is inclusion polymorphism or function overriding where a member function of a class is redefined with a different behavior from its parent class. This gets useful specially when the inheritance is truly polymorphic (that is, uses pure or non-pure virtual functions). This has also been discussed in depth in the class. You would recall how we used inclusion polymorphism for the draw() method over a hierarchy of shapes. You could use something similar for computing concessions and / or fare in different cases.

Exception classes would usually use static hierarchy because the catch clauses catch the exception by explicit type matching with hierarchical generalization. So using static overriding is the way to go.

</div>
</div>
<div class="layoutArea">
<div class="column">
38

</div>
</div>
</div>
<div class="page" title="Page 39">
<div class="layoutArea">
<div class="column">
B.1.7 Soumita Hait

</div>
</div>
<div class="layoutArea">
<div class="column">
<ol>
<li>Should constructors and destructor be included in the class diagram?PPD: It is optional, because it is mandatory for all classes.</li>
<li>Are the concession factors fixed or they can vary with time?PPD: They can change with time.</li>
<li>For the Master Data, it is given in the assignment that ”These should be hard-code inside the implemen- tation of functions / methods.” I cannot understand how to hard-code inside functions. Does it mean that I need to create static functions for setting/initializing the values of the various parameters?PPD: They should not be. It is a typo.</li>
<li>It is mentioned in the assignment that ”If there are more than one validation failures, the system should attempt to report as many of them as possible in a single run.” Sir, if an exception arises, it is thrown and detected by the corresponding catch block, after which the program is terminated. Then, how to detect more than one error in a single run? It is also given that we need to classify the exceptions using a hierarchy of Exceptions classes.PPD: Good question. Please note that raising an exception does not mean termination. If that is to be done, we can simply call exit(1). The whole idea of the exception is to raise-catch-handle and then proceed. That is get the system back to a consistent state. Also, if we are using exceptions, it does not mean that we cannot use other error trapping techniques, like flags, in sync with it. So an appropriate design for it is required.
That exceptions have a hierarchy, they are layered, are for advantages of deciding which kind of exception to catch where. Like the hierarchy of exceptions, the catch clauses should also be layered on the flow.

Exceptional design is not an easy task. It is good to think about handling such issues. Of course, as a user, if there are three independent errors in the input, you would not like to run the software thrice to get them. You would like to get them all together, fix and then go ahead. We need to design keeping that in mind.
</li>
</ol>
B.1.8 Suhas Jain

<ol>
<li>In section 1.3 Business Logic it is written that the tatkal charges are calculated on the base fare and then the load factor is multiplied to it. But in example 1.3.4 in the calculation, the tatkal charge is calculated after the base fare has been multiplied with the load factor. Which one should we follow?PPD: Follow the illustrative computations as shown in Sections 1.3.1, 1.3.2, 1.3.3, and 1.3.4.</li>
<li>In the Concessions class when we talk about a flat single level ad-hoc polymorphism, how are we supposed to design this? is it like we make a Divyaang class inherit from Concessions or we make separate classes for DivyaangBlind, DivyaangCancer …etc.?PPD: You can decide how you would design it. It is a matter of choice. I would rather perceive Concession and Divyaang as separate hierarchies because they are different concepts.
Of course, Concession class would need a kind of DivyaangConcession subclass where BookingClass and Divyaang information is mapped to the concession percentage.
</li>
<li>In the example of designing gender class by parametric polymorphism, why can’t we model name of the gender just like we did with salutation, why are we making a separate name attribute in the gender base class?PPD: You can. The name in the gender class is the name of the gender. Salutation can be mapped from this in the output handler. After all, we use male &amp; female to talk about gender and Mr. &amp; Ms. for salutation of the person. They are different concepts.</li>
</ol>
B.1.9 Yashica Patodia

1. I have a doubt if multiple booking categories are allowed for the same passenger?Like if a senior citizen can avail tatkal benefits and similar multiple other intersections

PPD: No. Not in the same booking. Only one category has to be chosen for a ticket. So it is either senior citizen or tatkal.

Of course, the same person can do different tickets in different categories.

</div>
</div>
<div class="layoutArea">
<div class="column">
39

</div>
</div>
</div>
