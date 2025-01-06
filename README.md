# Social Media Scheduler

A Rails-based social media scheduling app.

## **Project Overview**  
The **Social Media Scheduler** is a web-based application designed to streamline the process of creating, scheduling, and managing posts across platforms. It empowers users to optimize their social media strategy by providing an intuitive interface, scheduling automation, and robust role-based access controls.  

This project is built using **Ruby on Rails** and integrates seamlessly with background job processing systems like **Sidekiq** and **MySQL** for database management.  

---

## **Features**  
- **User Authentication**: Secure login system with encrypted passwords.  
- **Post Management**: Create, edit, delete, and schedule posts with specific visibility settings.  
- **Role-Based Access Control (RBAC)**: Admin, Moderator, and User roles with distinct permissions.  
- **Notifications**: Real-time updates for scheduled and published posts.  
- **Activity Logs**: Detailed logs of user activities for audit purposes.  
- **Search and Pagination**: Search posts by content and tags, with paginated results for efficiency.  
- **API Integration**: Expose API endpoints for external integrations.  
- **Cloud Scalability**: Designed to handle large-scale data with efficient database management.  

---

## **Technologies Used**  
- **Backend**: Ruby on Rails, Sidekiq, MySQL  
- **Frontend**: ERB Templates, JavaScript, CSS  
- **Authentication**: BCrypt-based secure authentication  
- **Job Scheduling**: Sidekiq for asynchronous background processing  
- **APIs**: Custom-built RESTful API endpoints  

---

## **Setup Instructions**  
1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/username/social_media_scheduler.git
   cd social_media_scheduler
   ```

2. **Install Dependencies**:  
   ```bash
   bundle install
   ```

3. **Set Up Database**:  
   Update the `database.yml` file with your credentials and run:  
   ```bash
   rails db:create db:migrate db:seed
   ```

4. **Start the Server**:  
   ```bash
   rails server
   ```

5. **Run Background Jobs**:  
   Start the Sidekiq worker process:  
   ```bash
   bundle exec sidekiq
   ```

---

## **Usage**  
1. Log in or register as a user.  
2. Create and schedule posts using the "New Post" interface.  
3. Monitor activity logs and notifications for updates on scheduled posts.  
4. Admins can manage users, categories, and view all system activities.  

---

## **Future Enhancements**  
- Integration with external social media APIs (e.g., Twitter, Facebook).  
- Advanced analytics dashboard for user engagement insights.  
- Mobile-friendly UI for enhanced accessibility.  

---

## **Contributors**  
- **LAXMIRANJAN SAHU** - Developer and Maintainer  

