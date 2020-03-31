Design Decisions:

- Multiple site-bd sections were created for each navigation tab for purposes of the demo. In a production application, configuration and routing would most likely be handled differently (e.g. React components, etc)
- Flexbox used on main sections for optimal layout and to easily adjust for responsive behavior. At breakpoint, top section can easily switch to column direction, sidebar to row direction, footer to column direction.
- Flexbox to allow video section to automatically adjust. Empty-space-child elements added to allow space-between justification while still wrapping to left edge on second row.
- Use of precentages and ems to prepare for responsiveness.
- Navigation tabs given equal width but could be adjusted if desired.
- Transition on pagination dots for effect.
