# 13-Rainmill-Ln-Inquiry
Adams Homes pre-construction landing pages
[13_rainmill_pl_COMPLETE.html](https://github.com/user-attachments/files/25316936/13_rainmill_pl_COMPLETE.html)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>13 Rainmill Pl - Pre-Construction Opportunity | Adams Homes</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Arial', sans-serif;
            background-color: #FFFFFF;
            color: #333;
            line-height: 1.6;
        }
        
        .logo-header {
            background-color: #FFFFFF;
            padding: 30px 20px 10px 20px;
            text-align: center;
            border-bottom: 4px solid #001489;
        }
        
        .logo-header img {
            max-width: 400px;
            height: auto;
            display: block;
            margin: 0 auto 15px auto;
        }
        
        .tagline {
            color: #001489;
            font-size: 20px;
            font-weight: 600;
            font-style: italic;
            margin-bottom: 20px;
        }
        
        .header {
            background: linear-gradient(135deg, #001489 0%, #698FCB 100%);
            color: white;
            padding: 40px 20px;
            text-align: center;
        }
        
        .header h1 {
            font-size: 36px;
            margin-bottom: 10px;
        }
        
        .header p {
            font-size: 20px;
            color: #FFFFFF;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background-color: white;
        }
        
        .section {
            padding: 50px 40px;
            border-bottom: 1px solid #C0C0C0;
        }
        
        .section:last-child {
            border-bottom: none;
        }
        
        .section h2 {
            color: #001489;
            font-size: 28px;
            margin-bottom: 20px;
            border-bottom: 3px solid #D50032;
            padding-bottom: 10px;
        }
        
        .section h3 {
            color: #001489;
            font-size: 22px;
            margin-top: 25px;
            margin-bottom: 15px;
        }
        
        .section p {
            font-size: 16px;
            margin-bottom: 15px;
            line-height: 1.8;
        }
        
        .section ul {
            margin-left: 25px;
            margin-bottom: 20px;
        }
        
        .section li {
            font-size: 16px;
            margin-bottom: 10px;
            line-height: 1.8;
        }
        
        .lot-details {
            background-color: #f8f9fa;
            border-left: 4px solid #D50032;
            padding: 20px;
            margin: 25px 0;
            border-radius: 4px;
        }
        
        .lot-details h3 {
            margin-top: 0;
            color: #001489;
        }
        
        .detail-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 15px;
            margin-top: 15px;
        }
        
        .detail-item {
            padding: 10px;
        }
        
        .detail-item strong {
            display: block;
            color: #001489;
            margin-bottom: 5px;
        }
        
        .benefits {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }
        
        .benefit-card {
            background-color: #f8f9fa;
            padding: 20px;
            border-radius: 8px;
            border-top: 3px solid #001489;
        }
        
        .benefit-card h4 {
            color: #001489;
            margin-bottom: 10px;
            font-size: 18px;
        }
        
        .benefit-card p {
            font-size: 15px;
            margin-bottom: 0;
        }
        
        .cta-box {
            background: linear-gradient(135deg, #001489 0%, #698FCB 100%);
            color: white;
            padding: 30px;
            border-radius: 8px;
            text-align: center;
            margin: 30px 0;
        }
        
        .cta-box h3 {
            color: white;
            margin-top: 0;
            font-size: 24px;
        }
        
        .cta-box p {
            font-size: 18px;
            margin-bottom: 0;
        }
        
        /* Form Styles */
        .form-section {
            background-color: #f8f9fa;
        }
        
        .form-group {
            margin-bottom: 25px;
        }
        
        label {
            display: block;
            margin-bottom: 8px;
            color: #333;
            font-weight: 600;
            font-size: 15px;
        }
        
        input[type="text"],
        input[type="email"],
        input[type="tel"],
        textarea {
            width: 100%;
            padding: 12px 15px;
            border: 2px solid #C0C0C0;
            border-radius: 4px;
            font-size: 16px;
            transition: border-color 0.3s;
            font-family: Arial, sans-serif;
        }
        
        input[type="text"]:focus,
        input[type="email"]:focus,
        input[type="tel"]:focus,
        textarea:focus {
            outline: none;
            border-color: #001489;
        }
        
        textarea {
            resize: vertical;
            min-height: 120px;
        }
        
        .submit-btn {
            background-color: #D50032;
            color: white;
            padding: 15px 40px;
            border: none;
            border-radius: 4px;
            font-size: 18px;
            font-weight: bold;
            cursor: pointer;
            width: 100%;
            transition: background-color 0.3s;
        }
        
        .submit-btn:hover {
            background-color: #a8002a;
        }
        
        .submit-btn:disabled {
            background-color: #C0C0C0;
            cursor: not-allowed;
        }
        
        .success-message {
            display: none;
            background-color: #d4edda;
            color: #155724;
            padding: 20px;
            border-radius: 4px;
            margin-bottom: 20px;
            border: 1px solid #c3e6cb;
            text-align: center;
        }
        
        .error-message {
            display: none;
            background-color: #f8d7da;
            color: #721c24;
            padding: 20px;
            border-radius: 4px;
            margin-bottom: 20px;
            border: 1px solid #f5c6cb;
            text-align: center;
        }
        
        .footer {
            background-color: #001489;
            color: white;
            text-align: center;
            padding: 30px 20px;
        }
        
        .footer p {
            margin-bottom: 10px;
            color: #FFFFFF;
        }
        
        .footer a {
            color: white;
            text-decoration: none;
        }
        
        .footer a:hover {
            text-decoration: underline;
        }
        
        .footer .disclaimer {
            font-size: 11px;
            margin-top: 20px;
            line-height: 1.4;
            color: #C0C0C0;
        }
        
        @media (max-width: 768px) {
            .logo-header img {
                max-width: 280px;
            }
            
            .tagline {
                font-size: 18px;
            }
            
            .header h1 {
                font-size: 28px;
            }
            
            .section {
                padding: 30px 20px;
            }
            
            .section h2 {
                font-size: 24px;
            }
            
            .detail-grid {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="logo-header">
        <img src="data:image/png;base64,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 ws5DjaiUlRdZGXSOx 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un5i8Bx ZNGqTshx1u7a1HQtRqS021ENKCM/ulnMGeBfEzP4jJppjESQeZH4KuRmcP/AD81S+ils9glT3pHnDRS2ewSp70jzi5OYqptpXu5henDmKqbaV7uYXpxma+71dT1ToBhyCpvRS2ewSp70jzhopbPYJU96R5xcnMVU20r3cwvThzFVNtK93ML04a+71dT00Aw5BU3opbPYJU96R5w0UtnsEqe9I84uTmKqbaV7uYXpw5iqm2le7mF6cNfd6up6aAYcgqb0UtnsEqe9I84aKWz2CVPekecXJzFVNtK93ML04cxVTbSvdzC9OGvu9XU9NAMOQVN6KWz2CVPekecNFLZ7BKnvSPOLk5iqm2le7mF6cOYqptpXu5henDX3erqemgGHIKm9FLZ7BKnvSPOGils9glT3pHnFycxVTbSvdzC9OHMVU20r3cwvThr7vV1PTQDDkFTeils9glT3pHnDRS2ewSp70jzi5OYqptpXu5henDmKqbaV7uYXpw193q6npoBhyCpvRS2ewSp70jzhopbPYJU96R5xcnMVU20r3cwvThzFVNtK93ML04a+71dT00Aw5BU3opbPYJU96R5w0UtnsEqe9I84uTmKqbaV7uYXpw5iqm2le7mF6cNfd6up6aAYcgqb0UtnsEqe9I84aKWz2CVPekecXJzFVNtK93ML04cxVTbSvdzC9OGvu9XU9NAMOQVN6KWz2CVPekecNFLZ7BKnvSPOLk5iqm2le7mF6cOYqptpXu5henDX3erqemgGHIKm9FLZ7BKnvSPOGils9glT3pHnFycxVTbSvdzC9OHMVU20r3cwvThr7vV1PTQDDkFTeils9glT3pHnDRS2ewSp70jzi5OYqptpXu5henDmKqbaV7uYXpw193q6npoBhyCpvRS2ewSp70jzhopbPYJU96R5xcnMVU20r3cwvThzFVNtK93ML04a+71dT00Aw5BU3opbPYJU96R5w0UtnsEqe9I84uTmKqbaV7uYXpw5iqm2le7mF6cNfd6up6aAYcgqb0UtnsEqe9I84aKWz2CVPekecXJzFVNtK93ML04cxVTbSvdzC9OGvu9XU9NAMOQVN6KWz2CVPekecNFLZ7BKnvSPOLk5iqm2le7mF6cOYqptpXu5henDX3erqemgGHIKm9FLZ7BKnvSPOGils9glT3pHnFycxVTbSvdzC9OHMVU20r3cwvThr7vV1PTQDDkFTeils9glT3pHnDRS2ewSp70jzi5OYqptpXu5henDmKqbaV7uYXpw193q6npoBhyCpvRS2ewSp70jzhopbPYJU96R5xcnMVU20r3cwvThzFVNtK93ML04a+71dT00Aw5BU3opbPYJU96R5w0UtnsEqe9I84uTmKqbaV7uYXpw5iqm2le7mF6cNfd6up6aAYcgqb0UtnsEqe9I84aKWz2CVPekecXJzFVNtK93ML04cxVTbSvdzC9OGvu9XU9NAMOQVN6KWz2CVPekecNFLZ7BKnvSPOLk5iqm2le7mF6cOYqptpXu5henDX3erqemgGHIKm9FLZ7BKnvSPOGils9glT3pHnFycxVTbSvdzC9OHMVU20r3cwvThr7vV1PTQDDkFTeils9glT3pHnDRS2ewSp70jzi5OYqptpXu5henDmKqbaV7uYXpw193q6npoBhyCpvRS2ewSp70jzhopbPYJU96R5xcnMVU20r3cwvThzFVNtK93ML04a+71dT00Aw5Bc3JLAg06232IFov2s0ctSjhvOEs1nmILjMSM9R4EX9UTAeSlRH4cdTUipy6is1monZKWkqIsC+z+rQgsNWPRjr6R6xrpX57y79fz2rIaLCyAACtSQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEQAAEX/2Q==" alt="Adams Homes">
        <div class="tagline">Value, simplified</div>
    </div>
    
    <div class="header">
        <h1>Pre-Construction Opportunity</h1>
        <p>13 Rainmill Pl, Palm Coast, FL 32164</p>
    </div>
    
    <div class="container">
        <!-- Lot Information Section -->
        <div class="section">
            <h2>Premium Lot Available</h2>
            <p>Discover this exceptional pre-construction lot opportunity in the desirable Palm Coast community. Choose from our proven floor plans and select your exterior and interior finishes to create a home that reflects your style, all backed by Adams Homes' trusted expertise and quality craftsmanship.</p>
            
            <div class="lot-details">
                <h3>Lot Details</h3>
                <div class="detail-grid">
                    <div class="detail-item">
                        <strong>Address:</strong>
                        13 Rainmill Pl
                    </div>
                    <div class="detail-item">
                        <strong>City:</strong>
                        Palm Coast, FL 32164
                    </div>
                    <div class="detail-item">
                        <strong>Community:</strong>
                        Palm Coast
                    </div>
                    <div class="detail-item">
                        <strong>Available:</strong>
                        Yes
                    </div>
                    <div class="detail-item">
                        <strong>School District:</strong>
                        Flagler County Schools
                    </div>
                </div>
            </div>
            
            <p>This prime location offers the perfect canvas for your new home, situated in one of Florida's most sought-after communities with easy access to beaches, shopping, dining, and local schools.</p>
        </div>
        
        <!-- Pre-Construction Process Section -->
        <div class="section">
            <h2>The Pre-Construction Advantage</h2>
            <p>When you purchase a pre-construction lot with Adams Homes, you're investing in a streamlined home-building experience with numerous benefits:</p>
            
            <div class="benefits">
                <div class="benefit-card">
                    <h4>Personalization Options</h4>
                    <p>Select your floor plan, then choose exterior and interior finishes plus add-on options to personalize your new home.</p>
                </div>
                <div class="benefit-card">
                    <h4>Price Lock</h4>
                    <p>Secure today's pricing and protect yourself from future price increases during construction.</p>
                </div>
                <div class="benefit-card">
                    <h4>Brand New and Warrantied</h4>
                    <p>Move into a brand new home with comprehensive warranty protection and the latest building standards.</p>
                </div>
                <div class="benefit-card">
                    <h4>Build Timeline</h4>
                    <p>Get on the construction schedule early and move into your new home sooner.</p>
                </div>
            </div>
            
            <h3>How It Works</h3>
            <ul>
                <li><strong>Step 1: Select A Lot</strong> - Find your new address!</li>
                <li><strong>Step 2: Choose Your Floor Plan</strong> - Select from our proven home designs</li>
                <li><strong>Step 3: Personalize Your Home</strong> - Pick your exterior and interior finishes and add-on options</li>
                <li><strong>Step 4: We Build</strong> - Our experienced team constructs your home with quality and care</li>
                <li><strong>Step 5: Move In</strong> - Enjoy your brand new, warrantied home!</li>
            </ul>
        </div>
        
        <!-- About Adams Homes Section -->
        <div class="section">
            <h2>Why Adams Homes?</h2>
            <p>In 1991, founder Wayne Adams drew from over a decade of homebuilding experience to begin serving homebuyers in Pensacola, Florida. Since then, Adams Homes has grown to become one of the largest, privately-held homebuilders in the country, building over 55,000 homes across the Southeastern United States.</p>
            
            <h3>Our Philosophy</h3>
            <p>We believe that a homebuilder should offer customers a straightforward purchase process that is easy to understand and a home that fits their needs from the beginning. While some homebuilders reduce the features included in their homes to sell high-priced upgrades, Adams Homes delivers value by offering homes that include the features most homebuyers want. In the words of Wayne Adams, "Regardless of price, size, or location, all buyers want their builder to deliver value."</p>
            
            <h3>Our Core Principles</h3>
            <ul>
                <li>You're only as good as the people with whom you surround yourself</li>
                <li>Keep it simple</li>
                <li>Treat people as you would want to be treated</li>
            </ul>
            
            <h3>Our Mission</h3>
            <p>To deliver value to our customers through a straightforward approach to building quality new homes - an approach that creates a win-win outcome for all parties involved.</p>
            
            <div class="cta-box">
                <h3>Ready to Build Your Dream Home?</h3>
                <p>Contact us today to learn more about this pre-construction opportunity and take the first step toward homeownership!</p>
            </div>
        </div>
        
        <!-- Contact Form Section -->
        <div class="section form-section">
            <h2>We're Here To Help</h2>
            <p>Interested in learning more about this lot or the pre-construction process? Fill out the form below and one of our knowledgeable sales representatives will contact you shortly.</p>
            
            <div class="success-message" id="successMessage">
                <strong>Thank you for your inquiry!</strong><br>
                We've received your information and will be in touch soon to discuss this exciting opportunity.
            </div>
            
            <div class="error-message" id="errorMessage">
                There was an error submitting your form. Please try again or contact us directly at (386) 254-5081.
            </div>
            
            <form id="contactForm" action="https://formspree.io/f/xqjjndaq" method="POST">
                <input type="hidden" name="property_address" value="13 Rainmill Pl, Palm Coast, FL 32164">
                <input type="hidden" name="_subject" value="Pre-Construction Inquiry - 13 Rainmill Pl, Palm Coast, FL">
                
                <div class="form-group">
                    <label for="firstName">First Name *</label>
                    <input type="text" id="firstName" name="first_name" required>
                </div>
                
                <div class="form-group">
                    <label for="lastName">Last Name *</label>
                    <input type="text" id="lastName" name="last_name" required>
                </div>
                
                <div class="form-group">
                    <label for="email">Email Address *</label>
                    <input type="email" id="email" name="email" required>
                </div>
                
                <div class="form-group">
                    <label for="phone">Phone Number *</label>
                    <input type="tel" id="phone" name="phone" required>
                </div>
                
                <div class="form-group">
                    <label for="comments">Comments</label>
                    <textarea id="comments" name="comments" placeholder="Tell us about your dream home or ask any questions..."></textarea>
                </div>
                
                <button type="submit" class="submit-btn" id="submitBtn">Submit Inquiry</button>
            </form>
        </div>
    </div>
    
    <div class="footer">
        <p><strong>Adams Homes - Palm Coast - Daytona Division</strong></p>
        <p><strong>Address:</strong> 1440 N Nova Rd #303, Daytona Beach, FL 32117</p>
        <p><strong>Phone:</strong> <a href="tel:3862545081">(386) 254-5081</a></p>
        <p class="disclaimer">*All information is deemed reliable but not guaranteed. Buyer to verify all information, including but not limited to HOA fees, school districts, and square footage.</p>
        <p style="margin-top: 20px; font-size: 14px;">© 2026 Adams Homes. All Rights Reserved.</p>
    </div>
    
    <script>
        const form = document.getElementById('contactForm');
        const submitBtn = document.getElementById('submitBtn');
        const successMessage = document.getElementById('successMessage');
        const errorMessage = document.getElementById('errorMessage');
        
        form.addEventListener('submit', async function(e) {
            e.preventDefault();
            
            successMessage.style.display = 'none';
            errorMessage.style.display = 'none';
            
            submitBtn.disabled = true;
            submitBtn.textContent = 'Submitting...';
            
            try {
                const response = await fetch(form.action, {
                    method: 'POST',
                    body: new FormData(form),
                    headers: {
                        'Accept': 'application/json'
                    }
                });
                
                if (response.ok) {
                    successMessage.style.display = 'block';
                    form.reset();
                    successMessage.scrollIntoView({ behavior: 'smooth', block: 'center' });
                } else {
                    errorMessage.style.display = 'block';
                    errorMessage.scrollIntoView({ behavior: 'smooth', block: 'center' });
                }
            } catch (error) {
                errorMessage.style.display = 'block';
                errorMessage.scrollIntoView({ behavior: 'smooth', block: 'center' });
            } finally {
                submitBtn.disabled = false;
                submitBtn.textContent = 'Submit Inquiry';
            }
        });
    </script>
</body>
</html>
