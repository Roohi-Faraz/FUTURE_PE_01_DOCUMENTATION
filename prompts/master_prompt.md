Build a professional, responsive web application called **“LocalBiz AI Copy Generator”** for **Future Interns Prompt Engineering – Task 1**.

## Project Goal

Create an AI-powered website copy generator that helps local businesses generate professional, simple, persuasive, website-ready content.

The application should allow a user to enter basic information about their business and generate:

1. Homepage Copy
2. Services Page Content
3. Call-to-Action (CTA) Sections

The generated content should be tailored to different local business types such as salons, cafes, clinics, agencies, restaurants, gyms, tutors, repair services, and other small businesses.

## Design

Create a clean, modern SaaS-style interface.

Use:

* Professional modern typography
* Clean white/light background
* Attractive but simple color palette
* Rounded cards and buttons
* Responsive design for desktop, tablet, and mobile
* Clear spacing and readable sections
* Professional dashboard-like layout

The website should look like a real client-ready AI product, not a basic demo.

## Page Structure

### 1. Header

Include:

* Logo: LocalBiz AI
* Navigation: Home, Generator, About
* A prominent “Start Generating” button

### 2. Hero Section

Headline:
“Create Website Copy That Helps Your Local Business Grow”

Subheading:
“Generate professional homepage, services, and CTA content tailored to your business in seconds.”

Include:

* “Generate Copy” button
* A small visual/card showing sample generated website content

### 3. Copy Generator

Create a form with these fields:

**Business Name**

* Text input

**Business Type**

* Dropdown:

  * Salon
  * Cafe
  * Restaurant
  * Clinic
  * Gym
  * Agency
  * Tutor
  * Repair Service
  * Retail Store
  * Other

**Location**

* Text input

**Target Customers**

* Text input

**Main Services**

* Large text area

**Unique Selling Point**

* Text area

**Brand Tone**

* Dropdown:

  * Professional
  * Friendly
  * Premium
  * Casual
  * Trustworthy
  * Modern

**Primary Goal**

* Dropdown:

  * Get More Calls
  * Get More Bookings
  * Get More Enquiries
  * Increase Store Visits
  * Generate Leads

Add a primary button:

“Generate Website Copy”

### 4. Generated Results

After generation, display three separate sections.

#### Homepage Copy

Generate:

* Hero headline
* Hero subheadline
* Value proposition
* Short business introduction
* Key benefits
* Trust-building section

#### Services

Generate a professional description for each service provided by the business.

For every service include:

* Service name
* Short description
* Customer benefit

#### CTA Section

Generate multiple CTA variations based on the user's selected business goal.

Examples of CTA purposes:

* Contact
* Book an appointment
* Request a quote
* Make an enquiry
* Visit the business

Each CTA should include:

* CTA heading
* Supporting sentence
* Button text

### 5. Copy Actions

For every generated section provide:

* Copy button
* Regenerate button
* Edit option

Also include:

* “Generate Again”
* “Copy All Content”
* “Download Copy” if practical

### 6. Prompt Logic

The application should use structured prompt logic so that generated content changes according to:

* Business type
* Location
* Target customers
* Services
* Unique selling point
* Brand tone
* Business goal

The generated copy must be:

* Simple
* Persuasive
* Clear
* Website-ready
* Customer-focused
* Appropriate for the selected business
* Free from unnecessary jargon
* Focused on conversion rather than generic descriptions

Do not generate the same generic copy for every business type.

For example, a salon should receive salon-specific language, while a clinic should receive trustworthy healthcare-oriented business copy, and a cafe should receive hospitality-focused copy.

### 7. AI Generation

If an AI API is available, structure the application so the generator can send the user's business information to an AI model using a structured prompt.

Use a prompt structure similar to:

“You are an expert website copywriter specializing in local businesses.

Create conversion-focused website copy for:

Business Name: {businessName}
Business Type: {businessType}
Location: {location}
Target Customers: {targetCustomers}
Services: {services}
Unique Selling Point: {usp}
Brand Tone: {tone}
Primary Goal: {goal}

Generate:

1. Homepage copy
2. Service descriptions
3. CTA sections

Requirements:

* Keep the language simple and natural.
* Clearly communicate customer benefits.
* Adapt the writing to the business type.
* Use the selected tone.
* Include location naturally where appropriate.
* Focus on the customer's needs.
* Make the content ready to paste directly into a website.
* Avoid generic filler text.”

If an API key is not available, create a realistic demo/mock generation system so the entire UI and workflow can still be demonstrated.

### 8. Example/Demo Mode

Include a “Try Example” option.

When clicked, automatically fill the form with an example local business such as:

Business Name: Glow Studio
Business Type: Salon
Location: Bengaluru
Target Customers: Women looking for professional hair and beauty services
Services: Haircuts, Hair coloring, Hair spa, Bridal makeup
Unique Selling Point: Personalized beauty services with experienced professionals
Brand Tone: Friendly
Primary Goal: Get More Bookings

Then generate the corresponding website copy.

### 9. About Section

Add an About section explaining:

“LocalBiz AI helps local businesses create professional website content using structured AI prompts. It transforms basic business information into homepage copy, service descriptions, and conversion-focused calls to action.”

### 10. Footer

Include:

* LocalBiz AI
* “AI-powered website copy for local businesses”
* Future Interns – Prompt Engineering Task 1
* GitHub placeholder
* Copyright

## Important UX Requirements

* Show loading state while generating content.
* Display useful validation messages if required fields are empty.
* Make the generated content easy to read.
* Make copy buttons functional.
* Ensure the application works well on mobile.
* Do not use excessive animations.
* Keep the interface professional and fast.
* Use reusable components and clean code.
* Make all buttons and interactions functional.
* Do not leave major UI elements as non-functional placeholders.

## Deliverable Goal

The final application should demonstrate the complete workflow:

Business Information → Structured Prompt → AI Website Copy → Homepage + Services + CTA → Copy/Edit/Regenerate

Build the application as a polished portfolio project suitable for demonstrating **Prompt Engineering skills** to a reviewer.

The project should clearly demonstrate:

* Prompt engineering
* Website copywriting
* Conversion-focused messaging
* Understanding of local business requirements
* AI content workflow
* Responsive web development

Do not add unrelated features that are outside the Task 1 requirements.
