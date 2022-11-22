
## Hospital Management System

### Admin/Agent
This is the main user,who has the followig capabilitites:
- Manage Doctor
- Manage Nurse
- Manage Patient
- Manage Bed


## Installation Steps:

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer update__
- Run __php artisan key:generate__
- Run __php artisan migrate__
- Run __php artisan db:seed__ (It has some seeded data for roles,permissions and default admin credentials)
- Run __php artisan storage:link__
- Run __php artisan serve__ to launch the main url.
