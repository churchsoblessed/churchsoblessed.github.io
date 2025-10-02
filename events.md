---
layout: page
title: Events
permalink: /events/
---

## Upcoming Events

Stay connected with what's happening at Church So Blessed International. Join us for worship services, special events, and community activities.

<div class="events-list">
{% assign sorted_events = site.events | sort: 'date' %}

{% if sorted_events.size > 0 %}
  {% for event in sorted_events %}
  <div class="event-item">
    <div class="event-date-badge">
      <span class="month">{{ event.date | date: "%b" }}</span>
      <span class="day">{{ event.date | date: "%d" }}</span>
      <span class="year">{{ event.date | date: "%Y" }}</span>
    </div>
    <div class="event-info">
      <h3><a href="{{ event.url | relative_url }}">{{ event.title }}</a></h3>
      <p class="event-time">⏰ {{ event.time }}</p>
      <p class="event-location">📍 {{ event.location }}</p>
      <p class="event-excerpt">{{ event.excerpt | strip_html | truncate: 150 }}</p>
      <a href="{{ event.url | relative_url }}" class="read-more">Read More →</a>
    </div>
  </div>
  {% endfor %}
{% else %}
  <p>No upcoming events at this time. Check back soon!</p>
{% endif %}
</div>

## Regular Schedule

**Sunday Services:**
- Morning Worship: 9:00 AM
- Evening Service: 6:00 PM

**Wednesday:**
- Bible Study: 7:00 PM

---

Want to stay updated on our events? [Contact us](/contact) to join our mailing list!
