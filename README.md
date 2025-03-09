# **Full-Stack Inventory Management Dashboard**  

[**Live Demo**](https://master.d11wcm85dyda28.amplifyapp.com/dashboard)  
[**Public Repository**](https://github.com/a1865818/inventory-management)  

## **Overview**  
This project is a complete **Full-Stack Inventory Management Dashboard Application** that showcases a robust and scalable solution for managing inventory. Built with **Next.js** for the frontend and styled using **Tailwind CSS**, the application includes advanced data handling through **Material UI Data Grid**. The backend, powered by **Node.js** with **Prisma ORM**, ensures efficient database interactions.  

The application integrates seamlessly with **AWS Services**, providing cloud-based solutions for deployment, database management, API creation, and storage. This repository includes a step-by-step guide to set up, build, and deploy the project, making it beginner-friendly while also catering to advanced users.

## **Features**  
- **Dynamic Inventory Dashboard**: Real-time visualization of inventory data using Material UI Data Grid.  
- **State Management**: Utilizes **Redux Toolkit** and **Redux Toolkit Query** for streamlined data fetching and state handling.  
- **Cloud Integration**: Leverages AWS services such as **RDS**, **S3**, **Amplify**, **EC2**, and **API Gateway** for cloud-based solutions.  
- **Responsive Design**: Built with **Tailwind CSS** for a seamless and modern UI across devices.  
- **Scalable Backend**: Developed using **Node.js** and **Prisma ORM** to handle complex database interactions.  
- **Beginner-Friendly AWS Guide**: Includes setup instructions, cost management tips, and networking basics for AWS services.  

---

## **Tech Stack**  

### **Frontend**  
- **Next.js**  
- **Tailwind CSS**  
- **Material UI Data Grid**  
- **Redux Toolkit**  
- **Redux Toolkit Query**  

### **Backend**  
- **Node.js**  
- **Prisma ORM**  

### **Cloud Services**  
- **AWS EC2**: For computing power and backend hosting.  
- **AWS RDS**: For relational database management.  
- **AWS API Gateway**: To create robust and scalable APIs.  
- **AWS Amplify**: For frontend deployment.  
- **AWS S3**: For storage solutions.  

---

## **Setup Instructions**  

### **1. Clone the Repository**  
```bash  
git clone <repository-url>  
cd inventory-management-dashboard  
```  

### **2. Install Dependencies**  

#### **Frontend Setup**  
```bash  
cd client  
npm install  
```  

#### **Backend Setup**  
```bash  
cd server  
npm install  
```  

### **3. Configure Environment Variables**  
Create a `.env` file in both `client` and `server` directories with the following keys:  

#### **Frontend (.env)**  
```env  
NEXT_PUBLIC_API_URL=<Your_API_Gateway_URL>  
```  

#### **Backend (.env)**  
```env  
DATABASE_URL=<Your_RDS_Database_Connection_String>  
AWS_ACCESS_KEY_ID=<Your_AWS_Access_Key>  
AWS_SECRET_ACCESS_KEY=<Your_AWS_Secret_Key>  
AWS_REGION=<Your_AWS_Region>  
```  

### **4. Start the Application**  

#### **Frontend**  
```bash  
cd client  
npm run dev  
```  

#### **Backend**  
```bash  
cd server  
npm start  
```  

Access the application at `http://localhost:3000`.  

---

## **AWS Integration**  

### **AWS Services Used**  
1. **RDS**: For relational database storage.  
2. **EC2**: For deploying the Node.js backend.  
3. **S3**: For storing and managing inventory files or images.  
4. **API Gateway**: To handle API requests and routing.  
5. **Amplify**: For deploying the Next.js frontend.  

### **AWS Setup**  
1. **Create an RDS Instance**: Set up a PostgreSQL database and update your `DATABASE_URL`.  
2. **Deploy Backend on EC2**:  
   - Launch an EC2 instance.  
   - Install Node.js and configure the server.  
   - Set up security groups to allow HTTP/HTTPS traffic.  
3. **Use API Gateway**: Create APIs for handling inventory management features.  
4. **Frontend Deployment on Amplify**: Connect your repository to Amplify for continuous deployment.  
5. **S3 Configuration**: Use S3 buckets for file storage and static asset management.  

---

## **Folder Structure**  
```
inventory-management-dashboard/  
│  
├── client/               # Next.js frontend  
│   ├── src/              # Source files  
│   ├── public/           # Static assets  
│   └── package.json      # Frontend dependencies  
│  
├── server/               # Node.js backend  
│   ├── prisma/           # Prisma schema files  
│   ├── routes/           # API routes  
│   ├── models/           # Database models  
│   └── package.json      # Backend dependencies  
│  
└── .env                  # Environment variables  
```  

---

## **Future Enhancements**  
- **User Authentication**: Add role-based access control for admins and staff.  
- **Notification System**: Alert users about low stock or critical inventory changes.  

---

## **Acknowledgments**  
- **AWS** for providing scalable cloud infrastructure.  
- **Prisma** for simplifying database interactions.  
- **Material UI** for robust data grid components.  


