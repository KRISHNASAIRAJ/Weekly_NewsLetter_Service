# Weekly NewsLetter Service

---

## Architecture

![image](https://github.com/KRISHNASAIRAJ/Weekly_NewsLetter_Service/assets/90061814/b2d0e790-9eea-43dd-b8be-4c14b1c70a68)
---
**Overview**

The Weekly Newsletter Service is a project designed to deliver curated big data news updates to subscribers on a weekly basis. Leveraging the power of AWS services, including S3, SES, Lambda, and Event Bridge.

---

**Features:**

- **AWS Integration:** The project utilizes various AWS services such as S3 for storage, SES for email sending, Lambda for serverless computing, and Event Bridge for scheduling.
  
- **Data Storage:** CSV files containing newsletter content and HTML templates are stored in AWS S3 buckets for easy access and management.
  
- **Email Delivery:** AWS SES is used to send out newsletters to subscribers, ensuring reliable and efficient delivery.

- **Serverless Computing:** AWS Lambda functions are employed to process HTML templates and subscriber lists, enabling scalability and cost-effectiveness.

- **Automated Scheduling:** Event Bridge is configured to trigger the Lambda function on a weekly basis, ensuring that newsletters are sent out consistently without manual intervention.

---

**Setup Instructions:**

1. **AWS Configuration:** Ensure that you have an AWS account set up with necessary permissions to access S3, SES, Lambda, and Event Bridge.

2. **S3 Bucket Setup:** Create S3 buckets to store CSV files containing newsletter content and HTML templates.

3. **SES Configuration:** Set up SES to enable sending emails and verify the email addresses used for sending newsletters.

4. **Lambda Function:** Create a Lambda function to process HTML templates and subscriber lists, and configure it to trigger on a weekly schedule using Event Bridge.

5. **Event Bridge Configuration:** Set up Event Bridge rules to trigger the Lambda function on a weekly basis.

6. **Testing:** Test the setup by uploading sample CSV files and HTML templates to the S3 bucket and verifying that newsletters are sent out as expected.

---

