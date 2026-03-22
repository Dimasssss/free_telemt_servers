# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-22 23:03:48 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 93444.7 (25h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3358641
telemt_connections_bad_total 267569
telemt_connections_current 865
telemt_connections_me_current 865
telemt_handshake_timeouts_total 106235
telemt_upstream_connect_attempt_total 34360
telemt_upstream_connect_success_total 34359
telemt_upstream_connect_attempts_per_request{bucket="1"} 34359
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11837
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22391
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 450
telemt_me_reconnect_attempts_total 1356
telemt_me_reconnect_success_total 564
telemt_me_reader_eof_total 580
telemt_me_idle_close_by_peer_total 580
telemt_me_route_drop_no_conn_total 2965779
telemt_me_route_drop_channel_closed_total 1229
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2806979
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 636
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 728
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 11973
telemt_desync_full_logged_total 3756
telemt_desync_suppressed_total 8217
telemt_desync_frames_bucket_total{bucket="1_2"} 3228
telemt_desync_frames_bucket_total{bucket="3_10"} 4373
telemt_desync_frames_bucket_total{bucket="gt_10"} 4372
telemt_pool_swap_total 103
telemt_pool_force_close_total 3200
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 633
telemt_me_draining_writers_reap_progress_total 31439
telemt_me_writer_removed_unexpected_total 560
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2295
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29372
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3144
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28239
telemt_me_writer_teardown_success_total{mode="normal"} 31667
telemt_me_writer_teardown_noop_total 31450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 62629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63117
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 373.830754
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63117
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 633
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 503
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 2796276
telemt_user_connections_current{user="hello"} 865
telemt_user_octets_from_client{user="hello"} 40000478916 (37.25 GB)
telemt_user_octets_to_client{user="hello"} 760035035668 (707.84 GB)
telemt_user_unique_ips_current{user="hello"} 357
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 106811.2 (29h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3960078
telemt_connections_bad_total 360616
telemt_connections_current 420
telemt_connections_me_current 420
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99983
telemt_upstream_connect_attempt_total 65241
telemt_upstream_connect_success_total 64444
telemt_upstream_connect_fail_total 705
telemt_upstream_connect_attempts_per_request{bucket="1"} 65149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28367
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 705
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 9485
telemt_me_reconnect_success_total 3477
telemt_me_reader_eof_total 3488
telemt_me_idle_close_by_peer_total 3488
telemt_me_route_drop_no_conn_total 3636370
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3149339
telemt_me_endpoint_quarantine_total 803
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 827
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 12848
telemt_desync_full_logged_total 7197
telemt_desync_suppressed_total 5651
telemt_desync_frames_bucket_total{bucket="1_2"} 2908
telemt_desync_frames_bucket_total{bucket="3_10"} 5043
telemt_desync_frames_bucket_total{bucket="gt_10"} 4897
telemt_pool_swap_total 98
telemt_pool_force_close_total 2959
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 243
telemt_me_draining_writers_reap_progress_total 42993
telemt_me_writer_removed_unexpected_total 3424
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5872
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40572
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2501
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 458
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40034
telemt_me_writer_teardown_success_total{mode="normal"} 46444
telemt_me_writer_teardown_noop_total 42994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89438
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.528311
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89438
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 243
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 3137
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 3160944
telemt_user_connections_current{user="hello"} 420
telemt_user_octets_from_client{user="hello"} 42757277921 (39.82 GB)
telemt_user_octets_to_client{user="hello"} 780907255904 (727.28 GB)
telemt_user_msgs_from_client{user="hello"} 45221
telemt_user_msgs_to_client{user="hello"} 178309
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 176
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 181671.1 (50h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16238156
telemt_connections_bad_total 1622780
telemt_connections_current 1084
telemt_connections_me_current 1084
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 396431
telemt_upstream_connect_attempt_total 80793
telemt_upstream_connect_success_total 80693
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 80710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39832
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39152
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1702
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2917
telemt_me_reconnect_success_total 1515
telemt_me_reader_eof_total 1460
telemt_me_idle_close_by_peer_total 1458
telemt_me_route_drop_no_conn_total 14033511
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12906659
telemt_me_endpoint_quarantine_total 1173
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1359
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 50
telemt_desync_total 53358
telemt_desync_full_logged_total 16922
telemt_desync_suppressed_total 36436
telemt_desync_frames_bucket_total{bucket="1_2"} 11861
telemt_desync_frames_bucket_total{bucket="3_10"} 20779
telemt_desync_frames_bucket_total{bucket="gt_10"} 20718
telemt_pool_swap_total 196
telemt_pool_force_close_total 6531
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1048
telemt_me_draining_writers_reap_progress_total 60536
telemt_me_writer_removed_unexpected_total 1408
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5245
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55970
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 54005
telemt_me_writer_teardown_success_total{mode="normal"} 61215
telemt_me_writer_teardown_noop_total 60589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 114313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 120143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 121194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 121765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 121795
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 121796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 121800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 121802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 121804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 121804
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 317.385920
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 121804
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1048
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 1309
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 12906879
telemt_user_connections_current{user="hello"} 1084
telemt_user_octets_from_client{user="hello"} 190143722505 (177.09 GB)
telemt_user_octets_to_client{user="hello"} 3468315285447 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 512
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 181672.9 (50h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11785652
telemt_connections_bad_total 1213724
telemt_connections_current 688
telemt_connections_me_current 688
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 344058
telemt_upstream_connect_attempt_total 95222
telemt_upstream_connect_success_total 93910
telemt_upstream_connect_fail_total 864
telemt_upstream_connect_attempts_per_request{bucket="1"} 94774
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39084
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3797
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 864
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4333
telemt_me_reconnect_success_total 1822
telemt_me_reader_eof_total 1683
telemt_me_idle_close_by_peer_total 1683
telemt_me_route_drop_no_conn_total 4545984
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8760545
telemt_me_endpoint_quarantine_total 1181
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1380
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 38625
telemt_desync_full_logged_total 12998
telemt_desync_suppressed_total 25627
telemt_desync_frames_bucket_total{bucket="1_2"} 9549
telemt_desync_frames_bucket_total{bucket="3_10"} 14844
telemt_desync_frames_bucket_total{bucket="gt_10"} 14232
telemt_pool_swap_total 193
telemt_pool_force_close_total 5899
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 58843
telemt_me_writer_removed_unexpected_total 1718
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5365
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55047
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52944
telemt_me_writer_teardown_success_total{mode="normal"} 60412
telemt_me_writer_teardown_noop_total 58868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 112562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 115760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 116905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 118096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 118855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 119195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 119270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 119272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 119278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 119280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 119280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 119280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 119280
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.272597
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 119280
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 135
telemt_me_writer_restored_same_endpoint_total 1554
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 8698365
telemt_user_connections_current{user="hello"} 688
telemt_user_octets_from_client{user="hello"} 217398330664 (202.47 GB)
telemt_user_octets_to_client{user="hello"} 3940734306199 (3.58 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 61
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 181636.5 (50h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10982524
telemt_connections_bad_total 958986
telemt_connections_current 563
telemt_connections_me_current 563
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 345075
telemt_upstream_connect_attempt_total 79311
telemt_upstream_connect_success_total 77760
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 77965
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35915
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37481
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5655
telemt_me_reconnect_success_total 2303
telemt_me_reader_eof_total 2043
telemt_me_idle_close_by_peer_total 2042
telemt_me_route_drop_no_conn_total 5328319
telemt_me_route_drop_channel_closed_total 383
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8310965
telemt_me_endpoint_quarantine_total 1262
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1337
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 68
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 37898
telemt_desync_full_logged_total 12567
telemt_desync_suppressed_total 25331
telemt_desync_frames_bucket_total{bucket="1_2"} 9570
telemt_desync_frames_bucket_total{bucket="3_10"} 14495
telemt_desync_frames_bucket_total{bucket="gt_10"} 13833
telemt_pool_swap_total 189
telemt_pool_force_close_total 5809
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 736
telemt_me_draining_writers_reap_progress_total 59039
telemt_me_writer_removed_unexpected_total 2197
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6090
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 55074
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 53230
telemt_me_writer_teardown_success_total{mode="normal"} 61164
telemt_me_writer_teardown_noop_total 59110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 114459
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 117167
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 118119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 119192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 119793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 120007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 120135
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 120166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 120174
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 120187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 120220
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 120223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 120274
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.635887
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 120274
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 736
telemt_me_refill_failed_total 178
telemt_me_writer_restored_same_endpoint_total 1994
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 8302967
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 192248955867 (179.05 GB)
telemt_user_octets_to_client{user="hello"} 3454412587973 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 247
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 51915.9 (14h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11123048
telemt_connections_bad_total 667495
telemt_connections_current 1061
telemt_connections_me_current 1061
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 256963
telemt_upstream_connect_attempt_total 53703
telemt_upstream_connect_success_total 50916
telemt_upstream_connect_fail_total 1891
telemt_upstream_connect_attempts_per_request{bucket="1"} 52807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26381
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5999
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1891
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7338
telemt_me_reconnect_success_total 1123
telemt_me_reader_eof_total 694
telemt_me_idle_close_by_peer_total 693
telemt_me_route_drop_no_conn_total 25270268
telemt_me_route_drop_channel_closed_total 58
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9238799
telemt_me_endpoint_quarantine_total 366
telemt_me_single_endpoint_outage_enter_total 84
telemt_me_single_endpoint_outage_exit_total 84
telemt_me_single_endpoint_outage_reconnect_attempt_total 157
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 157
telemt_me_single_endpoint_shadow_rotate_total 413
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 15933
telemt_desync_full_logged_total 4257
telemt_desync_suppressed_total 11676
telemt_desync_frames_bucket_total{bucket="1_2"} 3039
telemt_desync_frames_bucket_total{bucket="3_10"} 6440
telemt_desync_frames_bucket_total{bucket="gt_10"} 6454
telemt_pool_swap_total 53
telemt_pool_force_close_total 1815
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 464
telemt_me_draining_writers_reap_progress_total 15548
telemt_me_writer_removed_unexpected_total 1012
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2226
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14286
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1508
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13733
telemt_me_writer_teardown_success_total{mode="normal"} 16512
telemt_me_writer_teardown_noop_total 15567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32079
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32079
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.944565
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32079
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 464
telemt_me_refill_failed_total 331
telemt_me_writer_restored_same_endpoint_total 724
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 280
telemt_user_connections_total{user="hello"} 9264302
telemt_user_connections_current{user="hello"} 1061
telemt_user_octets_from_client{user="hello"} 86226274502 (80.30 GB)
telemt_user_octets_to_client{user="hello"} 579188536089 (539.41 GB)
telemt_user_msgs_from_client{user="hello"} 67224
telemt_user_msgs_to_client{user="hello"} 56168
telemt_user_unique_ips_current{user="hello"} 439
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 181642.6 (50h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10912453
telemt_connections_bad_total 929821
telemt_connections_current 781
telemt_connections_me_current 781
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 240300
telemt_upstream_connect_attempt_total 108105
telemt_upstream_connect_success_total 106979
telemt_upstream_connect_fail_total 954
telemt_upstream_connect_attempts_per_request{bucket="1"} 107933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 64393
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40993
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1355
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 954
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72760
telemt_me_reconnect_success_total 2991
telemt_me_reader_eof_total 2683
telemt_me_idle_close_by_peer_total 2681
telemt_me_route_drop_no_conn_total 5248861
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8617887
telemt_me_endpoint_quarantine_total 1205
telemt_me_single_endpoint_outage_enter_total 41
telemt_me_single_endpoint_outage_exit_total 41
telemt_me_single_endpoint_outage_reconnect_attempt_total 43
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 43
telemt_me_single_endpoint_shadow_rotate_total 1365
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 53
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 46002
telemt_desync_full_logged_total 15742
telemt_desync_suppressed_total 30260
telemt_desync_frames_bucket_total{bucket="1_2"} 9330
telemt_desync_frames_bucket_total{bucket="3_10"} 17607
telemt_desync_frames_bucket_total{bucket="gt_10"} 19065
telemt_pool_swap_total 185
telemt_pool_force_close_total 5503
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 656
telemt_me_draining_writers_reap_progress_total 63105
telemt_me_writer_removed_unexpected_total 2714
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6605
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59247
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4754
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57602
telemt_me_writer_teardown_success_total{mode="normal"} 65852
telemt_me_writer_teardown_noop_total 63106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 126824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 128222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 128641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128958
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.189972
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128958
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 656
telemt_me_refill_failed_total 4296
telemt_me_writer_restored_same_endpoint_total 2523
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8620952
telemt_user_connections_current{user="hello"} 781
telemt_user_octets_from_client{user="hello"} 193998145213 (180.67 GB)
telemt_user_octets_to_client{user="hello"} 3291631258296 (2.99 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 118478.8 (32h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11589819
telemt_connections_bad_total 463948
telemt_connections_current 638
telemt_connections_me_current 638
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4748329
telemt_upstream_connect_attempt_total 56275
telemt_upstream_connect_success_total 55858
telemt_upstream_connect_fail_total 405
telemt_upstream_connect_attempts_per_request{bucket="1"} 56263
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25446
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 405
telemt_me_reconnect_attempts_total 48733
telemt_me_reconnect_success_total 1749
telemt_me_reader_eof_total 1414
telemt_me_idle_close_by_peer_total 1413
telemt_me_route_drop_no_conn_total 4077229
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5572867
telemt_me_endpoint_quarantine_total 775
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 902
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31319
telemt_desync_full_logged_total 10665
telemt_desync_suppressed_total 20654
telemt_desync_frames_bucket_total{bucket="1_2"} 6216
telemt_desync_frames_bucket_total{bucket="3_10"} 12359
telemt_desync_frames_bucket_total{bucket="gt_10"} 12744
telemt_pool_swap_total 125
telemt_pool_force_close_total 3746
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 42199
telemt_me_writer_removed_unexpected_total 1467
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3586
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40121
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3305
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38453
telemt_me_writer_teardown_success_total{mode="normal"} 43707
telemt_me_writer_teardown_noop_total 42206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85913
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.640865
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85913
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 2730
telemt_me_writer_restored_same_endpoint_total 1553
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5565476
telemt_user_connections_current{user="hello"} 638
telemt_user_octets_from_client{user="hello"} 118716410852 (110.56 GB)
telemt_user_octets_to_client{user="hello"} 2151891618274 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 308
telemt_user_unique_ips_recent_window{user="hello"} 75
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 99449.5 (27h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1475972
telemt_connections_bad_total 36407
telemt_connections_current 455
telemt_connections_me_current 455
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 29408
telemt_upstream_connect_attempt_total 46497
telemt_upstream_connect_success_total 46350
telemt_upstream_connect_fail_total 119
telemt_upstream_connect_attempts_per_request{bucket="1"} 46469
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 774
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2135
telemt_me_reconnect_success_total 871
telemt_me_reader_eof_total 851
telemt_me_idle_close_by_peer_total 851
telemt_me_route_drop_no_conn_total 508466
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1310286
telemt_me_endpoint_quarantine_total 805
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 821
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 8305
telemt_desync_full_logged_total 2502
telemt_desync_suppressed_total 5803
telemt_desync_frames_bucket_total{bucket="1_2"} 2105
telemt_desync_frames_bucket_total{bucket="3_10"} 3212
telemt_desync_frames_bucket_total{bucket="gt_10"} 2988
telemt_pool_swap_total 107
telemt_pool_force_close_total 2783
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 39034
telemt_me_writer_removed_unexpected_total 823
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3069
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36823
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2695
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36251
telemt_me_writer_teardown_success_total{mode="normal"} 39892
telemt_me_writer_teardown_noop_total 39038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78930
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.033909
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78930
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 739
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 1306163
telemt_user_connections_current{user="hello"} 455
telemt_user_octets_from_client{user="hello"} 25591393657 (23.83 GB)
telemt_user_octets_to_client{user="hello"} 558411156535 (520.06 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 201
telemt_user_unique_ips_recent_window{user="hello"} 57
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 181647.5 (50h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13232679
telemt_connections_bad_total 1571083
telemt_connections_current 804
telemt_connections_me_current 804
telemt_handshake_timeouts_total 381062
telemt_upstream_connect_attempt_total 69874
telemt_upstream_connect_success_total 69533
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 69738
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34976
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 100
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2738
telemt_me_reconnect_success_total 1410
telemt_me_reader_eof_total 1386
telemt_me_idle_close_by_peer_total 1386
telemt_me_route_drop_no_conn_total 4474787
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10001661
telemt_me_endpoint_quarantine_total 1250
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1365
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 41790
telemt_desync_full_logged_total 13642
telemt_desync_suppressed_total 28148
telemt_desync_frames_bucket_total{bucket="1_2"} 10039
telemt_desync_frames_bucket_total{bucket="3_10"} 15376
telemt_desync_frames_bucket_total{bucket="gt_10"} 16375
telemt_pool_swap_total 201
telemt_pool_force_close_total 5456
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 667
telemt_me_draining_writers_reap_progress_total 63059
telemt_me_writer_removed_unexpected_total 1330
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5058
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 59377
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5282
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57603
telemt_me_writer_teardown_success_total{mode="normal"} 64435
telemt_me_writer_teardown_noop_total 63061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 124921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 126604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 126987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 127363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 127483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 127496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 127496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 127496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 127496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 127496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 127496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 127496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 127496
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.627638
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 127496
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 667
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 1236
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 78
telemt_user_connections_total{user="hello"} 9968420
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 194259740832 (180.92 GB)
telemt_user_octets_to_client{user="hello"} 4418931212476 (4.02 TB)
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 65
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 181643.9 (50h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11531660
telemt_connections_bad_total 1319867
telemt_connections_current 609
telemt_connections_me_current 609
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 306439
telemt_upstream_connect_attempt_total 96444
telemt_upstream_connect_success_total 95585
telemt_upstream_connect_fail_total 651
telemt_upstream_connect_attempts_per_request{bucket="1"} 96236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52054
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40551
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2067
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 651
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10137
telemt_me_reconnect_success_total 2476
telemt_me_reader_eof_total 2306
telemt_me_idle_close_by_peer_total 2305
telemt_me_seq_mismatch_total 88
telemt_me_route_drop_no_conn_total 5635065
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8904732
telemt_me_endpoint_quarantine_total 1420
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 50
telemt_me_single_endpoint_outage_exit_total 50
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 48
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 1368
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 48
telemt_desync_total 41499
telemt_desync_full_logged_total 13321
telemt_desync_suppressed_total 28178
telemt_desync_frames_bucket_total{bucket="1_2"} 10689
telemt_desync_frames_bucket_total{bucket="3_10"} 15261
telemt_desync_frames_bucket_total{bucket="gt_10"} 15549
telemt_pool_swap_total 191
telemt_pool_force_close_total 5250
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 653
telemt_me_draining_writers_reap_progress_total 62914
telemt_me_writer_removed_unexpected_total 2343
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6410
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 58927
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4779
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 57664
telemt_me_writer_teardown_success_total{mode="normal"} 65337
telemt_me_writer_teardown_noop_total 62919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 125577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 127351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 127887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 128206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 128256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 128256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 128256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 128256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 128256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 128256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 128256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 128256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 128256
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.357541
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 128256
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 653
telemt_me_refill_failed_total 396
telemt_me_writer_restored_same_endpoint_total 2002
telemt_me_writer_restored_fallback_total 122
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 219
telemt_user_connections_total{user="hello"} 8910111
telemt_user_connections_current{user="hello"} 609
telemt_user_octets_from_client{user="hello"} 156958534193 (146.18 GB)
telemt_user_octets_to_client{user="hello"} 3468291862439 (3.15 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 69
```