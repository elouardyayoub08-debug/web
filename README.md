# web
A website that talks about how bad smoking is for your body
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smoking: The Body's Enemy</title>
    <style>
        /* CSS will go here */
    </style>
</head>
<body>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Smoking: The Body's Enemy</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }
        
        header {
            background: linear-gradient(to right, #2c3e50, #4a6572);
            color: white;
            padding: 1rem;
            text-align: center;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
        }
        
        .header-content {
            max-width: 1200px;
            margin: 0 auto;
            display: flex;
            flex-direction: column;
            align-items: center;
            padding: 2rem 1rem;
        }
        
        h1 {
            font-size: 2.8rem;
            margin-bottom: 1rem;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        
        .subtitle {
            font-size: 1.2rem;
            max-width: 800px;
            margin-bottom: 1.5rem;
        }
        
        .stats-bar {
            background-color: #e74c3c;
            color: white;
            padding: 1rem;
            text-align: center;
            font-weight: bold;
        }
        
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 2rem;
        }
        
        .section {
            background-color: white;
            border-radius: 10px;
            padding: 2rem;
            margin-bottom: 2rem;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.08);
            transition: transform 0.3s ease;
        }
        
        .section:hover {
            transform: translateY(-5px);
        }
        
        h2 {
            color: #2c3e50;
            margin-bottom: 1.5rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #e74c3c;
            display: inline-block;
        }
        
        h3 {
            color: #e74c3c;
            margin: 1.5rem 0 1rem;
        }
        
        p {
            margin-bottom: 1rem;
        }
        
        .effects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1.5rem;
            margin-top: 2rem;
        }
        
        .effect-card {
            background: linear-gradient(to bottom right, #fff, #f8f9fa);
            border-left: 4px solid #e74c3c;
            padding: 1.5rem;
            border-radius: 8px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.05);
        }
        
        .icon {
            font-size: 2.5rem;
            color: #e74c3c;
            margin-bottom: 1rem;
        }
        
        .comparison {
            display: flex;
            justify-content: space-between;
            gap: 2rem;
            margin: 2rem 0;
        }
        
        .comparison-box {
            flex: 1;
            padding: 1.5rem;
            border-radius: 8px;
            text-align: center;
        }
        
        .healthy {
            background-color: #2ecc71;
            color: white;
        }
        
        .smoker {
            background-color: #e74c3c;
            color: white;
        }
        
        .image-placeholder {
            height: 200px;
            background-color: #ddd;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 1.5rem 0;
            color: #777;
            font-style: italic;
        }
        
        .stat-number {
            font-size: 2.5rem;
            font-weight: bold;
            color: #e74c3c;
            margin: 1rem 0;
        }
        
        .resources {
            background-color: #2c3e50;
            color: white;
            padding: 3rem 2rem;
            border-radius: 10px;
        }
        
        .resources h2 {
            color: white;
            border-bottom: 2px solid #e74c3c;
        }
        
        .resource-list {
            list-style-type: none;
            margin-top: 1.5rem;
        }
        
        .resource-list li {
            margin-bottom: 0.8rem;
            padding-left: 1.5rem;
            position: relative;
        }
        
        .resource-list li:before {
            content: "•";
            color: #e74c3c;
            font-weight: bold;
            position: absolute;
            left: 0;
        }
        
        .resource-list a {
            color: #3498db;
            text-decoration: none;
        }
        
        .resource-list a:hover {
            text-decoration: underline;
        }
        
        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 2rem;
            margin-top: 2rem;
        }
        
        .quote {
            font-style: italic;
            margin: 2rem 0;
            padding: 1.5rem;
            background-color: #f8f9fa;
            border-left: 4px solid #3498db;
            border-radius: 0 8px 8px 0;
        }
        
        @media (max-width: 768px) {
            .comparison {
                flex-direction: column;
            }
            
            h1 {
                font-size: 2.2rem;
            }
        }
    </style>
</head>
<body>
    <header>
        <div class="header-content">
            <h1>SMOKING: The Body's Enemy</h1>
            <p class="subtitle">Understanding the devastating impact of smoking on your health and body</p>
        </div>
    </header>
    
    <div class="stats-bar">
        <p>Smoking causes over 8 million deaths worldwide each year | 1.3 million of these deaths are non-smokers exposed to second-hand smoke</p>
    </div>
    
    <div class="container">
        <section class="section">
            <h2>How Smoking Affects Your Body</h2>
            <p>Smoking harms nearly every organ in your body. The chemicals in cigarette smoke enter your bloodstream and can travel throughout your body, causing damage everywhere they go.</p>
            
            <div class="image-placeholder">
                [Image: Comparison of healthy lungs vs smoker's lungs]
            </div>
            
            <div class="effects-grid">
                <div class="effect-card">
                    <div class="icon">
                        <i class="fas fa-lungs"></i>
                    </div>
                    <h3>Lungs & Respiratory System</h3>
                    <p>Smoking causes lung cancer, COPD, emphysema, and chronic bronchitis. It damages the airways and small air sacs in your lungs, making breathing difficult.</p>
                </div>
                
                <div class="effect-card">
                    <div class="icon">
                        <i class="fas fa-heartbeat"></i>
                    </div>
                    <h3>Heart & Circulatory System</h3>
                    <p>Smoking increases blood pressure, reduces circulation, and raises the risk of blood clots. It doubles your risk of heart attack and stroke.</p>
                </div>
                
                <div class="effect-card">
                    <div class="icon">
                        <i class="fas fa-brain"></i>
                    </div>
                    <h3>Brain & Nervous System</h3>
                    <p>Nicotine reaches your brain in seconds, making you feel energized. But as that effect wears off, you feel tired and crave more. Smoking increases risk of stroke.</p>
                </div>
                
                <div class="effect-card">
                    <div class="icon">
                        <i class="fas fa-tooth"></i>
                    </div>
                    <h3>Oral Health</h3>
                    <p>Smoking causes bad breath, tooth discoloration, inflammation of salivary glands, increased plaque buildup, gum disease, and oral cancer.</p>
                </div>
                
                <div class="effect-card">
                    <div class="icon">
                        <i class="fas fa-baby"></i>
                    </div>
                    <h3>Reproductive System</h3>
                    <p>Smoking can cause infertility, complications during pregnancy, premature birth, low birth weight, stillbirth, and sudden infant death syndrome (SIDS).</p>
                </div>
                
                <div class="effect-card">
                    <div class="icon">
                        <i class="fas fa-bone"></i>
                    </div>
                    <h3>Bones & Muscles</h3>
                    <p>Smoking reduces blood supply to bones and tissues, decreases calcium absorption, and increases risk of osteoporosis and fractures.</p>
                </div>
            </div>
        </section>
        
        <section class="section">
            <h2>Smoker vs. Non-Smoker: The Difference</h2>
            
            <div class="comparison">
                <div class="comparison-box healthy">
                    <h3>Healthy Non-Smoker</h3>
                    <ul>
                        <li>Normal lung function</li>
                        <li>Lower cancer risk</li>
                        <li>Healthy skin appearance</li>
                        <li>Better sense of taste and smell</li>
                        <li>Strong immune system</li>
                        <li>Longer life expectancy</li>
                    </ul>
                </div>
                
                <div class="comparison-box smoker">
                    <h3>Regular Smoker</h3>
                    <ul>
                        <li>Reduced lung capacity</li>
                        <li>High risk of various cancers</li>
                        <li>Premature skin aging</li>
                        <li>Diminished senses</li>
                        <li>Weakened immune system</li>
                        <li>10+ years shorter life expectancy</li>
                    </ul>
                </div>
            </div>
            
            <div class="stat-number">
                480,000 deaths annually in the U.S. are caused by smoking
            </div>
        </section>
        
        <section class="section">
            <h2>Chemicals in Cigarettes</h2>
            <p>A single cigarette contains over 7,000 chemicals. At least 70 of these are known to cause cancer. Here are some of the most dangerous:</p>
            
            <div class="image-placeholder">
                [Infographic: Chemicals in cigarettes with their other uses]
            </div>
            
            <h3>Dangerous Chemicals</h3>
            <ul>
                <li><strong>Nicotine</strong> - The addictive drug that keeps you smoking</li>
                <li><strong>Tar</strong> - Sticky residue that coats lungs and causes cancer</li>
                <li><strong>Carbon Monoxide</strong> - Poisonous gas that replaces oxygen in blood</li>
                <li><strong>Arsenic</strong> - Used in rat poison</li>
                <li><strong>Formaldehyde</strong> - Used to preserve dead bodies</li>
                <li><strong>Ammonia</strong> - Common household cleaner</li>
                <li><strong>Acetone</strong> - Found in nail polish remover</li>
            </ul>
            
            <div class="quote">
                "Smoking is the leading cause of preventable death worldwide. Quitting at any age can significantly reduce health risks and improve quality of life." - World Health Organization
            </div>
        </section>
        
        <section class="section resources">
            <h2>Resources to Quit Smoking</h2>
            <p>Quitting smoking is challenging but possible. Many resources are available to help you on your journey to becoming smoke-free:</p>
            
            <ul class="resource-list">
                <li><strong>Smoking cessation programs:</strong> Local hospitals and health departments often offer programs</li>
                <li><strong>Nicotine replacement therapy:</strong> Patches, gum, lozenges available over-the-counter</li>
                <li><strong>Prescription medications:</strong> Consult your doctor about options like Chantix or Zyban</li>
                <li><strong>Support groups:</strong> Both in-person and online communities can provide encouragement</li>
                <li><strong>Quitlines:</strong> 1-800-QUIT-NOW offers free coaching and support</li>
                <li><strong>Mobile apps:</strong> Try apps like QuitGuide or quitSTART to track progress</li>
            </ul>
            
            <div class="stat-number">
                Within 20 minutes of quitting, your heart rate and blood pressure drop
            </div>
        </section>
    </div>
    
    <footer>
        <p>This educational website is for informational purposes only. Consult a healthcare professional for medical advice.</p>
        <p>© 2023 Health Education Initiative</p>
    </footer>
</body>
</html>
