# OCLAPP1
OCL APPLICATIOn
 <mvc:View
    controllerName="your.namespace.controller.OCLScreen"
    xmlns:mvc="sap.ui.core.mvc"
    xmlns="sap.m">

    <Page title="OCL Screen">
        <content>
            <VBox>
                <HBox>
                    <Label text="Sales Order Number"/>
                    <Input id="salesOrderFrom" value="470340" width="150px"/>
                    <Label text="to"/>
                    <Input id="salesOrderTo" width="150px"/>
                    <Button text="Get Data" press="onGetData"/>
                </HBox>

                <Grid defaultSpan="L6 M6 S12" hSpacing="2" vSpacing="1">

                    <!-- Left Side -->
                    <Label text="Customer Code"/>
                    <Text text="10000429"/>

                    <Label text="Customer Name"/>
                    <Text text="RESHMA POULTRY FARM - ALEPHAT"/>

                    <Label text="Customer Location"/>
                    <Text text="MAHUWA"/>

                    <Label text="Average Monthly Volume Till Last Month"/>
                    <Text text="134.815"/>

                    <Label text="Current Month Volume"/>
                    <Text text="0.000"/>

                    <Label text="Sales Order Date"/>
                    <Text text="15.11.2022"/>

                    <Label text="Total Sales Order Qty (In MT)"/>
                    <Text text="40.000"/>

                    <Label text="Order Value"/>
                    <Text text="1,676,000.00"/>

                    <Label text="Credit Limit Days"/>
                    <Text text="15 Days"/>

                    <Label text="Total Credit Limit Rs"/>
                    <Text text="700,000.00"/>

                    <Label text="Total Opening Outstanding"/>
                    <Text text="348,186.00"/>

                    <Label text="Closing Outstanding"/>
                    <Text text="1,327,814.00"/>

                    <Label text="Dispatch Location"/>
                    <Text text="Ahmednagar"/>

                    <!-- Right Side -->
                    <Label text="Collateral Given As Cheque"/>
                    <Text text="CHEQUE"/>

                    <Label text="Cheque Valid Up To"/>
                    <Text text="00000000"/>

                    <Label text="Total Cheque Amount"/>
                    <Text text="1,200,000.00"/>

                    <Label text="Collateral Given As Bank Guarantee"/>
                    <Text text="00000000"/>

                    <Label text="Total Bank Guarantee Amount"/>
                    <Text text="0.00"/>

                    <Label text="Opening OS Not Due Rs."/>
                    <Text text="0.00"/>

                    <Label text="Opening OS Due/Overdue Rs."/>
                    <Text text="348,186.00"/>

                    <Label text="Total Credit Exposure"/>
                    <Text text="1,878,522.57"/>

                    <Label text="Value above credit limit (OCL Value)"/>
                    <Text text="1,178,522.57"/>

                    <Label text="Committed Payment Value Rs"/>
                    <Text text="550,022.57"/>

                    <Label text="Committed Payment Date"/>
                    <Text text="15.11.2022"/>

                    <Label text="Mode of Committed Payment"/>
                    <Text text="RTGS"/>

                    <Label text="Remarks of Sales Admin and Sales Manager"/>
                    <Text text="TEST 15.11.2023"/>
                </Grid>
            </VBox>
        </content>
    </Page>
</mvc:View>

