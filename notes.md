## Basic steps for RShiny app

##### User Interface
1. Begin each app with template
2. Add elements as arguments to fluidPage()
3. Create reactive inputs with *Input() functions
4. Display reactive results with an *Output() function
5. Assemble outputs from inputs in the server function

##### Server
1. Save the output that you build to output$
2. Build the output with a render*() function
3. Access input values with input$
Create reactivity by using Inputs to build rendered Outputs

### Input types (in UI)

* actionButton()
* submitButton()
* checkboxInput() = single checkbox
* checkboxGroupInput() = multiple checkbox
* dateInput() = blank box for inputting date
* dateRangeInput()
* fileInput()
* numericInput()
* passwordInput()
* radioButtons()
* selectInput() = drop-down selection
* sliderInput()
* textInput()

### Output types (in UI)

* dataTableOutput() = an interactive table
* htmlOutput() = raw HTML
* imageOutput() = image
* plotOutput() = plot
* tableOutput() = table
* textOutput() = text
* uiOutput() = a shiny UI element
* verbatimTextOutput() = text

### Render functions (in server)

* renderDataTable()
* renderImage
* renderPlot()
* renderPrint() = a code block of printed output
* renderTable()
* renderText
* renderUI() = a shiny UI element

Often a direct analog between render function and output function.
