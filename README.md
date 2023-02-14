
# Book-Finder App

This is a responsive web application made using HTML,CSS,Node.JS,React and API. This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app) . It takes in the name of the book and shows the availabilty of the book.


## Authors

- [Advaitaa Bhardwaj](https://github.com/advaitaa-02/)



## Deployment

To deploy this application on your computer follow the following steps.

       1. Clone this repository on your computer
       2. Open the main folder in VSCode or any other editor of your choice
       3. Run these commands in the main project directory
```bash
  npm i
  npm start
```
       4. After running the above commands your app should start running on a port 3000.

       5. After these steps, the webpage should look something like this:

       
![image](https://user-images.githubusercontent.com/92883292/218706172-6ca894ca-25fc-45c2-bf35-386b76c81114.png)


       6. Type any book name, for example It Ends with Us, and click on "Search button", the webpage would look like this:

![image](https://user-images.githubusercontent.com/92883292/218706614-97ba3ec7-2651-495a-b35f-99806be5e094.png)
  

        7. You can also click on the Home and the About section on the top right corner to navigate back to the Home and to know more about the site.


## API Reference

#### Get all items

```http
  GET /api/items
```

| Parameter | Type     | Description                |
| :-------- | :------- | :------------------------- |
| `api_key` | `string` | **Required**. Your API key |

#### Get item

```http
  GET /api/items/${id}
```

| Parameter | Type     | Description                       |
| :-------- | :------- | :-------------------------------- |
| `id`      | `string` | **Required**. Id of item to fetch |

#### add(num1, num2)

Takes two numbers and returns the sum.

