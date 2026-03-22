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

# Server Metrics 2026-03-22 13:14:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 58100.1 (16h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1795792
telemt_connections_bad_total 80773
telemt_connections_current 1654
telemt_connections_me_current 1654
telemt_handshake_timeouts_total 77779
telemt_upstream_connect_attempt_total 21873
telemt_upstream_connect_success_total 21872
telemt_upstream_connect_attempts_per_request{bucket="1"} 21872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14269
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 51
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 901
telemt_me_reconnect_success_total 356
telemt_me_reader_eof_total 360
telemt_me_idle_close_by_peer_total 360
telemt_me_route_drop_no_conn_total 1268487
telemt_me_route_drop_channel_closed_total 559
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1525284
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 404
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 461
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_desync_total 8631
telemt_desync_full_logged_total 2629
telemt_desync_suppressed_total 6002
telemt_desync_frames_bucket_total{bucket="1_2"} 2417
telemt_desync_frames_bucket_total{bucket="3_10"} 3248
telemt_desync_frames_bucket_total{bucket="gt_10"} 2966
telemt_pool_swap_total 64
telemt_pool_force_close_total 1920
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 312
telemt_me_draining_writers_reap_progress_total 19938
telemt_me_writer_removed_unexpected_total 351
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1419
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18732
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1884
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18018
telemt_me_writer_teardown_success_total{mode="normal"} 20151
telemt_me_writer_teardown_noop_total 19942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36311
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38069
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40093
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 150.506863
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40093
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 312
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 315
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1522407
telemt_user_connections_current{user="hello"} 1654
telemt_user_octets_from_client{user="hello"} 23729371296 (22.10 GB)
telemt_user_octets_to_client{user="hello"} 445802960720 (415.19 GB)
telemt_user_unique_ips_current{user="hello"} 656
telemt_user_unique_ips_recent_window{user="hello"} 254
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 71466.2 (19h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2935622
telemt_connections_bad_total 278083
telemt_connections_current 1597
telemt_connections_me_current 1597
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 68704
telemt_upstream_connect_attempt_total 46368
telemt_upstream_connect_success_total 45822
telemt_upstream_connect_fail_total 482
telemt_upstream_connect_attempts_per_request{bucket="1"} 46304
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 129
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 482
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3622
telemt_me_reconnect_success_total 1612
telemt_me_reader_eof_total 1487
telemt_me_idle_close_by_peer_total 1487
telemt_me_route_drop_no_conn_total 2712435
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2302830
telemt_me_endpoint_quarantine_total 602
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 33
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 559
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 8998
telemt_desync_full_logged_total 5034
telemt_desync_suppressed_total 3964
telemt_desync_frames_bucket_total{bucket="1_2"} 2110
telemt_desync_frames_bucket_total{bucket="3_10"} 3518
telemt_desync_frames_bucket_total{bucket="gt_10"} 3370
telemt_pool_swap_total 71
telemt_pool_force_close_total 2036
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 170
telemt_me_draining_writers_reap_progress_total 28341
telemt_me_writer_removed_unexpected_total 1446
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3110
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26678
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1792
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 244
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26305
telemt_me_writer_teardown_success_total{mode="normal"} 29788
telemt_me_writer_teardown_noop_total 28341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58098
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58126
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58129
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.410970
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58129
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 170
telemt_me_refill_failed_total 91
telemt_me_writer_restored_same_endpoint_total 1339
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 2314442
telemt_user_connections_current{user="hello"} 1597
telemt_user_octets_from_client{user="hello"} 28215863667 (26.28 GB)
telemt_user_octets_to_client{user="hello"} 537598345094 (500.68 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1005
telemt_user_unique_ips_recent_window{user="hello"} 830
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 146326.0 (40h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13513998
telemt_connections_bad_total 1187743
telemt_connections_current 5280
telemt_connections_me_current 5280
telemt_handshake_timeouts_total 344023
telemt_upstream_connect_attempt_total 53226
telemt_upstream_connect_success_total 53144
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2429
telemt_me_reconnect_success_total 1272
telemt_me_reader_eof_total 1214
telemt_me_idle_close_by_peer_total 1213
telemt_me_route_drop_no_conn_total 11528580
telemt_me_route_drop_channel_closed_total 117
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10827500
telemt_me_endpoint_quarantine_total 931
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1088
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
telemt_me_writers_active_current 44
telemt_desync_total 44225
telemt_desync_full_logged_total 14068
telemt_desync_suppressed_total 30157
telemt_desync_frames_bucket_total{bucket="1_2"} 10000
telemt_desync_frames_bucket_total{bucket="3_10"} 17280
telemt_desync_frames_bucket_total{bucket="gt_10"} 16945
telemt_pool_swap_total 157
telemt_pool_force_close_total 5376
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 849
telemt_me_draining_writers_reap_progress_total 48550
telemt_me_writer_removed_unexpected_total 1171
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4222
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44833
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4946
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 430
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43174
telemt_me_writer_teardown_success_total{mode="normal"} 49055
telemt_me_writer_teardown_noop_total 48598
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 88520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 97637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97653
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 244.132975
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97653
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 849
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1095
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 10815605
telemt_user_connections_current{user="hello"} 5280
telemt_user_octets_from_client{user="hello"} 157284415280 (146.48 GB)
telemt_user_octets_to_client{user="hello"} 2923021702148 (2.66 TB)
telemt_user_unique_ips_current{user="hello"} 2058
telemt_user_unique_ips_recent_window{user="hello"} 1204
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 146327.4 (40h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10072050
telemt_connections_bad_total 931045
telemt_connections_current 5764
telemt_connections_me_current 5764
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 302604
telemt_upstream_connect_attempt_total 79611
telemt_upstream_connect_success_total 78474
telemt_upstream_connect_fail_total 816
telemt_upstream_connect_attempts_per_request{bucket="1"} 79290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3676
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 816
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3617
telemt_me_reconnect_success_total 1441
telemt_me_reader_eof_total 1320
telemt_me_idle_close_by_peer_total 1320
telemt_me_route_drop_no_conn_total 4030637
telemt_me_route_drop_channel_closed_total 419
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7521799
telemt_me_endpoint_quarantine_total 917
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 1109
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 33829
telemt_desync_full_logged_total 11399
telemt_desync_suppressed_total 22430
telemt_desync_frames_bucket_total{bucket="1_2"} 8337
telemt_desync_frames_bucket_total{bucket="3_10"} 13020
telemt_desync_frames_bucket_total{bucket="gt_10"} 12472
telemt_pool_swap_total 156
telemt_pool_force_close_total 4796
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 46782
telemt_me_writer_removed_unexpected_total 1352
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4225
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 43777
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4384
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 412
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41986
telemt_me_writer_teardown_success_total{mode="normal"} 48002
telemt_me_writer_teardown_noop_total 46797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 92796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 93797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 94457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 94744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 94789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 94791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 94797
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 94799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 94799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 94799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 94799
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 87.905363
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 94799
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 118
telemt_me_writer_restored_same_endpoint_total 1226
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 7461770
telemt_user_connections_current{user="hello"} 5764
telemt_user_octets_from_client{user="hello"} 191552956377 (178.40 GB)
telemt_user_octets_to_client{user="hello"} 3376466842442 (3.07 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2253
telemt_user_unique_ips_recent_window{user="hello"} 734
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 146300.5 (40h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9547172
telemt_connections_bad_total 799958
telemt_connections_current 5298
telemt_connections_me_current 5298
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 307799
telemt_upstream_connect_attempt_total 64906
telemt_upstream_connect_success_total 64064
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 64241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30814
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30068
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1177
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2005
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 655
telemt_me_reconnect_attempts_total 3958
telemt_me_reconnect_success_total 1743
telemt_me_reader_eof_total 1534
telemt_me_idle_close_by_peer_total 1533
telemt_me_route_drop_no_conn_total 4315441
telemt_me_route_drop_channel_closed_total 310
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7199697
telemt_me_endpoint_quarantine_total 1000
telemt_me_single_endpoint_outage_enter_total 26
telemt_me_single_endpoint_outage_exit_total 26
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 1072
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 81
telemt_desync_total 33581
telemt_desync_full_logged_total 11148
telemt_desync_suppressed_total 22433
telemt_desync_frames_bucket_total{bucket="1_2"} 8541
telemt_desync_frames_bucket_total{bucket="3_10"} 12861
telemt_desync_frames_bucket_total{bucket="gt_10"} 12179
telemt_pool_swap_total 152
telemt_pool_force_close_total 4730
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 632
telemt_me_draining_writers_reap_progress_total 47348
telemt_me_writer_removed_unexpected_total 1657
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4666
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44262
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4239
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 491
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42618
telemt_me_writer_teardown_success_total{mode="normal"} 48928
telemt_me_writer_teardown_noop_total 47415
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 93780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 94594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 96242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 96249
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 96262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 96294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 96294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 96343
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3108.825762
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 96343
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 632
telemt_me_refill_failed_total 113
telemt_me_writer_restored_same_endpoint_total 1523
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 54
telemt_me_writer_removed_unexpected_minus_restored_total 127
telemt_user_connections_total{user="hello"} 7192696
telemt_user_connections_current{user="hello"} 5298
telemt_user_octets_from_client{user="hello"} 170394379037 (158.69 GB)
telemt_user_octets_to_client{user="hello"} 3026679711617 (2.75 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1417
telemt_user_unique_ips_recent_window{user="hello"} 878
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 16571.6 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6974205
telemt_connections_bad_total 441488
telemt_connections_current 6388
telemt_connections_me_current 6388
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 109870
telemt_upstream_connect_attempt_total 27568
telemt_upstream_connect_success_total 26235
telemt_upstream_connect_fail_total 1009
telemt_upstream_connect_attempts_per_request{bucket="1"} 27244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14708
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1009
telemt_me_keepalive_timeout_total 629
telemt_me_reconnect_attempts_total 2593
telemt_me_reconnect_success_total 467
telemt_me_reader_eof_total 289
telemt_me_idle_close_by_peer_total 289
telemt_me_route_drop_no_conn_total 16759156
telemt_me_route_drop_channel_closed_total 26
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5805055
telemt_me_endpoint_quarantine_total 107
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 136
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 8574
telemt_desync_full_logged_total 2205
telemt_desync_suppressed_total 6369
telemt_desync_frames_bucket_total{bucket="1_2"} 1551
telemt_desync_frames_bucket_total{bucket="3_10"} 3458
telemt_desync_frames_bucket_total{bucket="gt_10"} 3565
telemt_pool_swap_total 15
telemt_pool_force_close_total 624
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 4422
telemt_me_writer_removed_unexpected_total 421
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4012
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 180
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3798
telemt_me_writer_teardown_success_total{mode="normal"} 4800
telemt_me_writer_teardown_noop_total 4425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7506
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9225
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.794017
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9225
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 112
telemt_me_writer_restored_same_endpoint_total 311
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 107
telemt_user_connections_total{user="hello"} 5820390
telemt_user_connections_current{user="hello"} 6388
telemt_user_octets_from_client{user="hello"} 31472848143 (29.31 GB)
telemt_user_octets_to_client{user="hello"} 172790847456 (160.92 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2341
telemt_user_unique_ips_recent_window{user="hello"} 1310
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 146298.3 (40h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9260094
telemt_connections_bad_total 774095
telemt_connections_current 5157
telemt_connections_me_current 5157
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 199978
telemt_upstream_connect_attempt_total 89348
telemt_upstream_connect_success_total 88451
telemt_upstream_connect_fail_total 775
telemt_upstream_connect_attempts_per_request{bucket="1"} 89226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 54960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32031
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 775
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71233
telemt_me_reconnect_success_total 2396
telemt_me_reader_eof_total 2126
telemt_me_idle_close_by_peer_total 2125
telemt_me_route_drop_no_conn_total 4480626
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7318390
telemt_me_endpoint_quarantine_total 978
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1095
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 52
telemt_desync_total 37423
telemt_desync_full_logged_total 12817
telemt_desync_suppressed_total 24606
telemt_desync_frames_bucket_total{bucket="1_2"} 7597
telemt_desync_frames_bucket_total{bucket="3_10"} 14440
telemt_desync_frames_bucket_total{bucket="gt_10"} 15386
telemt_pool_swap_total 150
telemt_pool_force_close_total 4428
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 536
telemt_me_draining_writers_reap_progress_total 50055
telemt_me_writer_removed_unexpected_total 2154
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5285
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46940
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3823
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 605
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45627
telemt_me_writer_teardown_success_total{mode="normal"} 52225
telemt_me_writer_teardown_noop_total 50056
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100507
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101984
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102281
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.397792
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102281
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 536
telemt_me_refill_failed_total 4248
telemt_me_writer_restored_same_endpoint_total 2010
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 7320126
telemt_user_connections_current{user="hello"} 5157
telemt_user_octets_from_client{user="hello"} 170096494467 (158.41 GB)
telemt_user_octets_to_client{user="hello"} 2798810478477 (2.55 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1972
telemt_user_unique_ips_recent_window{user="hello"} 634
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 83134.2 (23h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9082476
telemt_connections_bad_total 320234
telemt_connections_current 4176
telemt_connections_me_current 4176
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3823324
telemt_upstream_connect_attempt_total 41592
telemt_upstream_connect_success_total 41292
telemt_upstream_connect_fail_total 293
telemt_upstream_connect_attempts_per_request{bucket="1"} 41585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23696
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17483
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 113
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 293
telemt_me_reconnect_attempts_total 47899
telemt_me_reconnect_success_total 1430
telemt_me_reader_eof_total 1097
telemt_me_idle_close_by_peer_total 1097
telemt_me_route_drop_no_conn_total 3297944
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4383840
telemt_me_endpoint_quarantine_total 550
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 627
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 24023
telemt_desync_full_logged_total 8046
telemt_desync_suppressed_total 15977
telemt_desync_frames_bucket_total{bucket="1_2"} 4874
telemt_desync_frames_bucket_total{bucket="3_10"} 9443
telemt_desync_frames_bucket_total{bucket="gt_10"} 9706
telemt_pool_swap_total 87
telemt_pool_force_close_total 2703
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 278
telemt_me_draining_writers_reap_progress_total 29033
telemt_me_writer_removed_unexpected_total 1162
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2636
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27587
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2301
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 402
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26330
telemt_me_writer_teardown_success_total{mode="normal"} 30223
telemt_me_writer_teardown_noop_total 29040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59263
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.849834
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59263
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 278
telemt_me_refill_failed_total 2701
telemt_me_writer_restored_same_endpoint_total 1277
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4378835
telemt_user_connections_current{user="hello"} 4176
telemt_user_octets_from_client{user="hello"} 97106751376 (90.44 GB)
telemt_user_octets_to_client{user="hello"} 1689261094254 (1.54 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1616
telemt_user_unique_ips_recent_window{user="hello"} 614
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 64104.9 (17h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 740056
telemt_connections_bad_total 8518
telemt_connections_current 1036
telemt_connections_me_current 1036
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14088
telemt_upstream_connect_attempt_total 32704
telemt_upstream_connect_success_total 32622
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 32691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 397
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1455
telemt_me_reconnect_success_total 624
telemt_me_reader_eof_total 606
telemt_me_idle_close_by_peer_total 606
telemt_me_route_drop_no_conn_total 248859
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 666529
telemt_me_endpoint_quarantine_total 578
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 537
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 3663
telemt_desync_full_logged_total 1079
telemt_desync_suppressed_total 2584
telemt_desync_frames_bucket_total{bucket="1_2"} 892
telemt_desync_frames_bucket_total{bucket="3_10"} 1449
telemt_desync_frames_bucket_total{bucket="gt_10"} 1322
telemt_pool_swap_total 68
telemt_pool_force_close_total 1680
telemt_me_writer_close_signal_drop_total 97
telemt_me_draining_writers_reap_progress_total 26830
telemt_me_writer_removed_unexpected_total 586
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2056
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25382
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1603
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25150
telemt_me_writer_teardown_success_total{mode="normal"} 27438
telemt_me_writer_teardown_noop_total 26832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 54245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54270
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.998160
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54270
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 97
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 541
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 668166
telemt_user_connections_current{user="hello"} 1036
telemt_user_octets_from_client{user="hello"} 12654371957 (11.79 GB)
telemt_user_octets_to_client{user="hello"} 318479397371 (296.61 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 327
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 146302.6 (40h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11306060
telemt_connections_bad_total 1317438
telemt_connections_current 5765
telemt_connections_me_current 5765
telemt_handshake_timeouts_total 304467
telemt_upstream_connect_attempt_total 55367
telemt_upstream_connect_success_total 55152
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 55319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27199
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27906
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_reconnect_attempts_total 2179
telemt_me_reconnect_success_total 1156
telemt_me_reader_eof_total 1121
telemt_me_idle_close_by_peer_total 1121
telemt_me_route_drop_no_conn_total 3563226
telemt_me_route_drop_channel_closed_total 94
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8493650
telemt_me_endpoint_quarantine_total 1007
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1099
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 34712
telemt_desync_full_logged_total 11388
telemt_desync_suppressed_total 23324
telemt_desync_frames_bucket_total{bucket="1_2"} 8301
telemt_desync_frames_bucket_total{bucket="3_10"} 12839
telemt_desync_frames_bucket_total{bucket="gt_10"} 13572
telemt_pool_swap_total 162
telemt_pool_force_close_total 4444
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 561
telemt_me_draining_writers_reap_progress_total 49877
telemt_me_writer_removed_unexpected_total 1076
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4088
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46901
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4293
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45433
telemt_me_writer_teardown_success_total{mode="normal"} 50989
telemt_me_writer_teardown_noop_total 49879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98801
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100868
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.113230
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100868
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 561
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1012
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8464436
telemt_user_connections_current{user="hello"} 5765
telemt_user_octets_from_client{user="hello"} 163421342352 (152.20 GB)
telemt_user_octets_to_client{user="hello"} 3818185678396 (3.47 TB)
telemt_user_unique_ips_current{user="hello"} 2066
telemt_user_unique_ips_recent_window{user="hello"} 825
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 146299.5 (40h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9778337
telemt_connections_bad_total 1095711
telemt_connections_current 4859
telemt_connections_me_current 4859
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 254427
telemt_upstream_connect_attempt_total 80764
telemt_upstream_connect_success_total 80174
telemt_upstream_connect_fail_total 510
telemt_upstream_connect_attempts_per_request{bucket="1"} 80684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44401
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32862
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2002
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 510
telemt_me_reconnect_attempts_total 8542
telemt_me_reconnect_success_total 1913
telemt_me_reader_eof_total 1785
telemt_me_idle_close_by_peer_total 1785
telemt_me_seq_mismatch_total 71
telemt_me_route_drop_no_conn_total 4349640
telemt_me_route_drop_channel_closed_total 307
telemt_me_route_drop_queue_full_total 16
telemt_me_route_drop_queue_full_profile_total{profile="high"} 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7525174
telemt_me_endpoint_quarantine_total 1115
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 34
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1103
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_me_writers_active_current 88
telemt_desync_total 33909
telemt_desync_full_logged_total 11074
telemt_desync_suppressed_total 22835
telemt_desync_frames_bucket_total{bucket="1_2"} 8402
telemt_desync_frames_bucket_total{bucket="3_10"} 12632
telemt_desync_frames_bucket_total{bucket="gt_10"} 12875
telemt_pool_swap_total 155
telemt_pool_force_close_total 4284
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 542
telemt_me_draining_writers_reap_progress_total 49019
telemt_me_writer_removed_unexpected_total 1810
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5078
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45817
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3921
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 363
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44735
telemt_me_writer_teardown_success_total{mode="normal"} 50895
telemt_me_writer_teardown_noop_total 49023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 99134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 99918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99918
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.904660
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99918
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 542
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1556
telemt_me_writer_restored_fallback_total 95
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 7532523
telemt_user_connections_current{user="hello"} 4859
telemt_user_octets_from_client{user="hello"} 133398561337 (124.24 GB)
telemt_user_octets_to_client{user="hello"} 2981801131823 (2.71 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 2023
telemt_user_unique_ips_recent_window{user="hello"} 561
```