# GriffNode.SDK.Model.RecurringWebhookPayload
Recurring payment request event. schedule_id + your own reference identify the customer/order. The period's payment also fires the normal payment.* events. 

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**Id** | **string** |  | 
**Event** | **string** |  | 
**Timestamp** | **DateTime** |  | 
**ScheduleId** | **Guid** |  | 
**Reference** | **string** | Your own customer/order id, as entered on the schedule. | [optional] 
**CustomerEmail** | **string** |  | [optional] 
**Description** | **string** |  | [optional] 
**AmountFiat** | **string** | Decimal string. | [optional] 
**CurrencyFiat** | **string** |  | [optional] 
**Interval** | **string** |  | [optional] 
**Status** | **string** |  | 
**PeriodNo** | **int** | recurring.payment.* only. | [optional] 
**TransactionId** | **string** | recurring.payment.completed only. | [optional] 
**Reason** | **string** | recurring.stopped only. | [optional] 

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)

