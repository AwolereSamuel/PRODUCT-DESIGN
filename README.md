# PRODUCT-DESIGN AND PRODUCT MANAGEMENT
**Executive Summary.**

The Group 16 Logistics Route Optimization Platform is a proposed digital solution designed to help logistics companies plan, monitor and execute deliveries more efficiently. The platform combines real-time traffic information, route optimization, alternative route recommendations, delivery tracking, driver navigation, automated dispatch and performance analytics. The product addresses a common operational challenge in logistics: delivery routes are often planned without sufficient consideration of changing traffic conditions, road closures, road accessibility, delivery sequence and customer expectations. These limitations can result in delayed deliveries, higher fuel consumption, increased operational costs and poor customer satisfaction.
  
  The proposed platform is intended to serve two principal user groups:

- Logistics managers and dispatchers, who need visibility over delivery operations, vehicle movements, route performance and delivery progress.

- Delivery drivers, who need clear navigation, delivery instructions, route changes, incident reporting and delivery confirmation tools.

  The supplied prototype demonstrates several core flows, including driver registration, driver login, customer login, account creation, route review, navigation initiation, package delivery, delivery confirmation, order placement and delivery time review.

  From a product management perspective, the concept has a relevant business problem, identifiable users and a logical set of operational features. However, the product would benefit from clearer role-based permissions, stronger prioritisation of the minimum viable product, a more explicit data model, improved accessibility, clearer error and exception states, and a more measurable validation strategy.

  ## PROJECT OVERVIEW
  **Product Description.**

  The Group 16 Logistics Route Optimization Platform is a logistics technology product intended to improve the movement of goods from a base station or dispatch location to customers or designated pickup stations. The platform is expected to use real-time traffic information and route optimization logic to recommend routes that minimize delays and operational inefficiencies. Unlike a general-purpose navigation application, the product is designed around logistics-specific requirements such as:

1. Multiple delivery locations.

2. Delivery sequence optimisation.

3. Dispatch management.

4. Driver assignment.

5. Package confirmation.

6. Customer delivery visibility.

7. Traffic-based rerouting.

8. Delivery performance analytics.

The product is positioned as an affordable, logistics-focused platform for small and medium-sized businesses, while retaining the ability to scale to larger operations.

**Product Category.**
- Logistics technology.

- Route optimisation.

- Fleet operations.

- Delivery management.

- Mobility and navigation.

- Business intelligence and analytics.

**Product Objectives.**

The product objectives identified in the PRD are:

1. Reduce average delivery time by 25%.

2. Decrease fuel costs by 10%.

3. Improve customer satisfaction by 35%.

**Problem Statement.**

Core Problem:-
Logistics companies face difficulties optimising delivery routes in real time because traffic congestion, road closures, road conditions and other disruptions can change after a route has been planned.

When route planning does not adapt to real-world conditions, logistics companies may experience:

- Late deliveries.

- Increased fuel consumption.

- Higher vehicle operating costs.

- Inefficient driver utilisation.

- Poor coordination between dispatchers and drivers.

- Limited visibility into delivery progress.

- Reduced customer satisfaction.

- Increased manual workload for logistics personnel.

The PRD identifies unpredictable traffic conditions, road closures and inefficient route planning as key sources of operational inefficiency.

**User-Level Problem.**

A driver may receive a route that appears efficient based on distance but becomes inefficient because of congestion or road closures. The driver may then need to make an independent decision without adequate information or dispatch support.

A logistics manager may also lack a centralised view of:

1. Which drivers are active.

2. Which deliveries are delayed.

3. Which routes are congested.

4. Which orders have been completed.

5. Which delivery exceptions require intervention.

**Business Impact.**

If the problem remains unresolved, a logistics company may face:

- Increased cost per delivery.

- Lower daily delivery capacity.

- Poor customer retention.

- More customer complaints.

- Higher fuel expenditure.

- Reduced operational predictability.

- Increased dependency on manual coordination.

  ## CORE SOLUTION COMPONENTS

**1. Real-Time Traffic Intelligence.**

The platform will integrate traffic data from external sources and other available data providers. This information may include:

- Traffic congestion.

- Road closures.

- Road incidents.

- Estimated travel time.

- Route disruptions.

- Weather-related route risks, where data is available.

**2. Route Optimisation Engine.**

 The route engine will evaluate available routes using factors such as:-

- Travel time.

- Traffic congestion.

- Road closures.

- Number of delivery stops.

- Delivery priority.

- Vehicle constraints.

- Estimated fuel consumption.

- Customer delivery windows.

The PRD specifies that the route with less traffic should be preferred over a route that is merely shorter in distance. This principle should be explicitly defined as a product rule and validated with logistics operators.

**3. Driver Navigation.**

Drivers will receive:

- An assigned delivery route.

- Turn-by-turn directions.

- Delivery sequence.

- Traffic updates.

- Rerouting recommendations.

- Delivery confirmation tools.

- Incident reporting options.

**4. Dispatch and Monitoring.**

Dispatchers or logistics managers will be able to:

- Review delivery assignments.

- Monitor active drivers.

- View route progress.

- Respond to route disruptions.

- Review delivery exceptions.

- Track delivery completion.

**5. Customer Visibility.**

Customers will be able to access delivery information, including:

- Estimated delivery time.

- Delivery status.

- Selected pickup or delivery option.

- A route or tracking link.

- Relevant delivery notifications.

## TARGET USERS AND PERSONAS

**Primary Persona: Logistics Manager.**

Role: Manages delivery operations, drivers and route assignments.

Goals:-

(i) Reduce delivery delays.

(ii) Monitor delivery activity.

(iii) Improve driver productivity.

(iv) Reduce fuel and operational costs.

(v) Respond quickly to disruptions.

(vi) Review delivery performance.

**Pain Points:**

(i) Manual route planning.

(ii) Limited visibility into driver locations.

(iii) Difficulty identifying delayed deliveries.

(iv) Fragmented communication with drivers.

(v) Lack of historical route performance data.

**Key Product Needs:**

(i) Operations dashboard.

(ii) Route planning.

(iii) Driver assignment.

(iv) Live delivery tracking.

(v) Alerts and exception management.

(vi) Analytics and reports.

**Secondary Persona: Delivery Driver.**

Role: Collects and delivers packages according to assigned instructions.

Goals:

(i) Receive clear delivery assignments.

(ii) Navigate efficiently.

(iii) Avoid traffic-related delays.

(iv) Confirm successful deliveries.

(v) Report incidents quickly.

(vi) Understand the next delivery stop.

**Pain Points:**

(i) Changing traffic conditions.

(ii) Incomplete delivery information.

(iii) Manual communication with dispatchers.

(iv) Unclear delivery sequence.

(v) Difficulty documenting unsuccessful deliveries.

**Key Product Needs:**

(i) Driver login.

(ii) Daily delivery overview.

(iii) Route navigation.

(iv) Rerouting notifications.

(v) Package scanning and confirmation.

(vi) Incident reporting.

**Additional Persona: Customer.**

Although the PRD focuses mainly on logistics managers and drivers, the customer is an important secondary stakeholder.

Goals:

(i) Know when an order will arrive.

(ii) Track delivery progress.

(iii) Receive timely updates.

(iv) Select a convenient delivery or pickup option.

(v) Contact the logistics provider when necessary.

**Key Product Needs:**

(i) Order creation.

(ii) Delivery estimate.

(iii) Delivery status.

(iv) Tracking link.

(v) Notification preferences.

(vi) Delivery confirmation information.

## REVIEW OF THE AVAILABLE PROTOTYPE

The Figma overview shows a collection of mobile-oriented screens for different user journeys. The visible screens include:

1. Group 16 Logistics Company landing or welcome screen.

2. Driver registration.

3. Driver login.

4. User login.

5. Route review.

6. Traffic-related route information.

7. Navigation initiation.

8. Package delivery.

9. Delivery confirmation.

10. Delivery time review.

11. Customer account creation.

12. Order creation.

13. Order placement confirmation.

14. User dashboard or welcome navigation.

## FUNCTIONAL REQUIREMENT

**Authentication and Account Management.**

The platform should allow users to:

(i) Create an account.

(ii) Log in securely.

(iii) Verify their email address.

(iv) Reset forgotten passwords.

(v) Manage profile information.

(vi) Update selected account settings.

(vii) Contact customer support for restricted changes.

**Driver Registration Data.**

The prototype and PRD show fields such as:

1. Full name

2. Address

3. NIN/BVN reference

4. Guarantor information

5. Passport photograph

6. Password

These fields require additional policy and security review. Sensitive identity information should only be collected when legally justified, operationally necessary and securely protected. The product team should define:

- Why each field is required.

- Who can access the information.

- How long it will be retained.

- Whether the information can be replaced with a less sensitive identifier.

- How consent and privacy notices will be presented.

**Customer Order Information.**

The customer flow should capture:

(i) Origin or base station.

(ii) Preferred pickup or delivery option.

(iii) Pickup station, if selected.

(iv) Home delivery address, if selected.

(v) Primary mobile number.

(vi) Alternative contact number.

(vii) Order details.

(viii) Delivery preferences.

**The three proposed fulfilment options are:**

1 Pickup station

2 Available station on route

3 Home delivery

The interface should clearly explain the implications, availability and potential cost of each option.

**Route Planning and Optimisation.**

Users should be able to:

(i) Enter one or multiple delivery locations.

(ii) Review the planned delivery sequence.

(iii) View estimated travel time.

(iv) Compare route alternatives.

(v) Receive traffic-based recommendations.

(vi) Avoid selected route types, where supported.

(vii) Start navigation.

(viii) Recalculate routes when conditions change.

**Traffic and Incident Information.**

The platform should provide:

1. Live traffic information.

2. Road closure alerts.

3. Incident notifications.

4. Alternative route suggestions.

5. Traffic-related estimated time changes.

6. User or driver incident reports, where supported.

The product should communicate the confidence and timestamp of traffic information. Users should not be presented with an apparently precise estimate when the data is uncertain or outdated.

**Delivery Tracking.**

The system should support:

(i) Driver location updates.

(ii) Delivery status changes.

(iii) Estimated arrival time.

(iv) Customer tracking links.

(v) Dispatcher monitoring.

(vi) Delivery completion records.

(vi) Exception status.

Suggested delivery statuses:

- Order received

- Order confirmed

- Awaiting dispatch

- Assigned to driver

- Driver en route to pickup

- Package collected

- In transit

- Near destination

- Delivered

- Delivery failed

- Rescheduled

- Cancelled

**Package Delivery Confirmation.**

The driver should be able to:

- Scan a package.

- Confirm delivery.

- Record delivery time.

- Add delivery notes.

- Report customer unavailability.

- Record failed delivery reasons.

- Upload supporting evidence if required by company policy.

**Notifications.**

The platform should support notifications for:

- Traffic congestion.

- Road closures.

- Route changes.

- Driver assignment.

- Delivery status updates.

- Estimated arrival changes.

- Failed delivery attempts.

- Customer order updates.

The PRD proposes constant email notifications about traffic conditions. This should be refined to avoid excessive notifications and notification fatigue.

A better approach is to allow users to configure:

(i) Routes of interest.

(ii) Notification channels.

(iii) Notification frequency.

(iv) Severity thresholds.

(v) Quiet hours.

(vi) Delivery status events.


## NON-FUNCTIONAL REQUIREMENT 

**Performance.**

The platform should provide responsive interactions and timely updates.

Recommended performance considerations:

- Fast loading of route information.

- Low-latency delivery status updates.

- Efficient map rendering.

- Graceful handling of weak internet connections.

- Background synchronisation for mobile devices.

- Clear loading, error and retry states.

**Scalability.**

The system should be designed to support growth in:

(i) Number of logistics companies.

(ii) Number of registered drivers.

(iii) Number of active deliveries.

(iv) Number of route calculations.

(v) Volume of traffic data.

(vi) Number of simultaneous users.


**Security.**

Security controls should include:

1. Secure authentication.

2. Password hashing.

3. Role-based access control.

4. Encryption in transit.

5. Encryption at rest for sensitive information.

6. Audit logs for important actions.

7. Secure API authentication.

8. Session management.

9. Rate limiting.

10. Secure storage of identity documents.

11. Data minimisation.

**Usability.**

The interface should:

- Use clear and familiar language.

- Make the next action obvious.

- Reduce unnecessary form fields.

- Provide visible feedback after user actions.

- Support error correction.

- Use consistent button labels.

- Avoid relying only on colour to communicate status.

- Support use in bright outdoor environments.

**Accessibility.**

The design should consider:

(i) Sufficient colour contrast.

(ii) Readable text sizes.

(iii) Touch target sizes.

(iv) Screen-reader compatibility.

(v) Clear error messages.

(vi) Non-colour status indicators.

(vii) Voice guidance.

(viii) Support for users with visual or hearing impairments.
