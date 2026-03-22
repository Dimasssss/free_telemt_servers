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

# Server Metrics 2026-03-22 05:39:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 30808.7 (8h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537876
telemt_connections_bad_total 35813
telemt_connections_current 1119
telemt_connections_me_current 1119
telemt_handshake_timeouts_total 28216
telemt_upstream_connect_attempt_total 12707
telemt_upstream_connect_success_total 12706
telemt_upstream_connect_attempts_per_request{bucket="1"} 12706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4462
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8213
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 20
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 330
telemt_me_reconnect_success_total 198
telemt_me_reader_eof_total 194
telemt_me_idle_close_by_peer_total 194
telemt_me_route_drop_no_conn_total 115832
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 445282
telemt_me_endpoint_quarantine_total 234
telemt_me_single_endpoint_shadow_rotate_total 257
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_desync_total 3938
telemt_desync_full_logged_total 1084
telemt_desync_suppressed_total 2854
telemt_desync_frames_bucket_total{bucket="1_2"} 1321
telemt_desync_frames_bucket_total{bucket="3_10"} 1495
telemt_desync_frames_bucket_total{bucket="gt_10"} 1122
telemt_pool_swap_total 34
telemt_pool_force_close_total 908
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 11492
telemt_me_writer_removed_unexpected_total 191
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 794
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 10877
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 898
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10584
telemt_me_writer_teardown_success_total{mode="normal"} 11671
telemt_me_writer_teardown_noop_total 11493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 22285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 22680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 22858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23164
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.391350
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23164
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 180
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 444285
telemt_user_connections_current{user="hello"} 1119
telemt_user_octets_from_client{user="hello"} 5976488080 (5.57 GB)
telemt_user_octets_to_client{user="hello"} 158084034976 (147.23 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 429
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 44175.1 (12h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 995441
telemt_connections_bad_total 79003
telemt_connections_current 1454
telemt_connections_me_current 1454
telemt_handshake_timeouts_total 33833
telemt_upstream_connect_attempt_total 23475
telemt_upstream_connect_success_total 23151
telemt_upstream_connect_fail_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 23443
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11831
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11270
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 292
telemt_me_reconnect_attempts_total 1754
telemt_me_reconnect_success_total 634
telemt_me_reader_eof_total 556
telemt_me_idle_close_by_peer_total 556
telemt_me_route_drop_no_conn_total 379696
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 771479
telemt_me_endpoint_quarantine_total 410
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 357
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 23
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
telemt_me_writers_warm_current 24
telemt_desync_total 3306
telemt_desync_full_logged_total 1914
telemt_desync_suppressed_total 1392
telemt_desync_frames_bucket_total{bucket="1_2"} 689
telemt_desync_frames_bucket_total{bucket="3_10"} 1271
telemt_desync_frames_bucket_total{bucket="gt_10"} 1346
telemt_pool_swap_total 47
telemt_pool_force_close_total 1233
telemt_me_writer_close_signal_drop_total 92
telemt_me_draining_writers_reap_progress_total 18209
telemt_me_writer_removed_unexpected_total 530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1548
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17204
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16976
telemt_me_writer_teardown_success_total{mode="normal"} 18752
telemt_me_writer_teardown_noop_total 18209
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36723
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36947
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36961
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.138100
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36961
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 92
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 474
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 773190
telemt_user_connections_current{user="hello"} 1454
telemt_user_octets_from_client{user="hello"} 12272290755 (11.43 GB)
telemt_user_octets_to_client{user="hello"} 285616737834 (266.00 GB)
telemt_user_msgs_from_client{user="hello"} 6021
telemt_user_msgs_to_client{user="hello"} 9976
telemt_user_unique_ips_current{user="hello"} 902
telemt_user_unique_ips_recent_window{user="hello"} 289
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 119035.0 (33h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8314642
telemt_connections_bad_total 722140
telemt_connections_current 2611
telemt_connections_me_current 2611
telemt_handshake_timeouts_total 270115
telemt_upstream_connect_attempt_total 44365
telemt_upstream_connect_success_total 44287
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 44295
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24037
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 183
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1650
telemt_me_reconnect_success_total 865
telemt_me_reader_eof_total 873
telemt_me_idle_close_by_peer_total 873
telemt_me_route_drop_no_conn_total 4646282
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6659679
telemt_me_endpoint_quarantine_total 759
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 895
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_me_writers_active_current 43
telemt_desync_total 28113
telemt_desync_full_logged_total 9373
telemt_desync_suppressed_total 18740
telemt_desync_frames_bucket_total{bucket="1_2"} 6076
telemt_desync_frames_bucket_total{bucket="3_10"} 10990
telemt_desync_frames_bucket_total{bucket="gt_10"} 11047
telemt_pool_swap_total 129
telemt_pool_force_close_total 4263
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 645
telemt_me_draining_writers_reap_progress_total 40526
telemt_me_writer_removed_unexpected_total 841
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3345
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37526
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4016
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 247
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36263
telemt_me_writer_teardown_success_total{mode="normal"} 40871
telemt_me_writer_teardown_noop_total 40570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 79423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81441
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 169.408829
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81441
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 645
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 772
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 6650977
telemt_user_connections_current{user="hello"} 2611
telemt_user_octets_from_client{user="hello"} 112912873432 (105.16 GB)
telemt_user_octets_to_client{user="hello"} 2262723544484 (2.06 TB)
telemt_user_unique_ips_current{user="hello"} 1060
telemt_user_unique_ips_recent_window{user="hello"} 431
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 119036.4 (33h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6838820
telemt_connections_bad_total 605601
telemt_connections_current 2821
telemt_connections_me_current 2821
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 229026
telemt_upstream_connect_attempt_total 48294
telemt_upstream_connect_success_total 47893
telemt_upstream_connect_fail_total 204
telemt_upstream_connect_attempts_per_request{bucket="1"} 48097
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23648
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 558
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 204
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2054
telemt_me_reconnect_success_total 930
telemt_me_reader_eof_total 908
telemt_me_idle_close_by_peer_total 908
telemt_me_route_drop_no_conn_total 2347486
telemt_me_route_drop_channel_closed_total 287
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5116486
telemt_me_endpoint_quarantine_total 756
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 917
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 23728
telemt_desync_full_logged_total 8137
telemt_desync_suppressed_total 15591
telemt_desync_frames_bucket_total{bucket="1_2"} 5691
telemt_desync_frames_bucket_total{bucket="3_10"} 9212
telemt_desync_frames_bucket_total{bucket="gt_10"} 8825
telemt_pool_swap_total 130
telemt_pool_force_close_total 3853
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 394
telemt_me_draining_writers_reap_progress_total 38902
telemt_me_writer_removed_unexpected_total 887
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3214
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36518
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3635
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35049
telemt_me_writer_teardown_success_total{mode="normal"} 39732
telemt_me_writer_teardown_noop_total 38908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 75088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 76770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78640
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.964646
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78640
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 394
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 811
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 66
telemt_user_connections_total{user="hello"} 5037934
telemt_user_connections_current{user="hello"} 2821
telemt_user_octets_from_client{user="hello"} 146913474537 (136.82 GB)
telemt_user_octets_to_client{user="hello"} 2411701801299 (2.19 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1135
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 119001.6 (33h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6677101
telemt_connections_bad_total 563211
telemt_connections_current 2398
telemt_connections_me_current 2398
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 223115
telemt_upstream_connect_attempt_total 54717
telemt_upstream_connect_success_total 54166
telemt_upstream_connect_fail_total 143
telemt_upstream_connect_attempts_per_request{bucket="1"} 54309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25183
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 758
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 143
telemt_me_keepalive_timeout_total 72
telemt_me_reconnect_attempts_total 2464
telemt_me_reconnect_success_total 1073
telemt_me_reader_eof_total 1011
telemt_me_idle_close_by_peer_total 1011
telemt_me_route_drop_no_conn_total 2351096
telemt_me_route_drop_channel_closed_total 144
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4970033
telemt_me_endpoint_quarantine_total 851
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 886
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
telemt_me_writers_active_current 44
telemt_desync_total 23624
telemt_desync_full_logged_total 8023
telemt_desync_suppressed_total 15601
telemt_desync_frames_bucket_total{bucket="1_2"} 5738
telemt_desync_frames_bucket_total{bucket="3_10"} 9059
telemt_desync_frames_bucket_total{bucket="gt_10"} 8827
telemt_pool_swap_total 128
telemt_pool_force_close_total 3730
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 417
telemt_me_draining_writers_reap_progress_total 39939
telemt_me_writer_removed_unexpected_total 1001
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3452
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37504
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3488
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 242
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36209
telemt_me_writer_teardown_success_total{mode="normal"} 40956
telemt_me_writer_teardown_noop_total 39951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80532
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80907
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 36.991227
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80907
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 417
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 938
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 4964454
telemt_user_connections_current{user="hello"} 2398
telemt_user_octets_from_client{user="hello"} 137840756239 (128.37 GB)
telemt_user_octets_to_client{user="hello"} 2273480470327 (2.07 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 979
telemt_user_unique_ips_recent_window{user="hello"} 474
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 119039.7 (33h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21344112
telemt_connections_bad_total 1809844
telemt_connections_current 3729
telemt_connections_me_current 3729
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 650985
telemt_upstream_connect_attempt_total 210566
telemt_upstream_connect_success_total 191893
telemt_upstream_connect_fail_total 16760
telemt_upstream_connect_attempts_per_request{bucket="1"} 208653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 133140
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46924
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1954
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9875
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16760
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 65497
telemt_me_reconnect_success_total 2545
telemt_me_reader_eof_total 1590
telemt_me_idle_close_by_peer_total 1589
telemt_me_route_drop_no_conn_total 40333942
telemt_me_route_drop_channel_closed_total 130
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17149229
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 929
telemt_me_single_endpoint_outage_enter_total 153
telemt_me_single_endpoint_outage_exit_total 153
telemt_me_single_endpoint_outage_reconnect_attempt_total 322
telemt_me_single_endpoint_outage_reconnect_success_total 80
telemt_me_single_endpoint_quarantine_bypass_total 322
telemt_me_single_endpoint_shadow_rotate_total 937
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
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
telemt_desync_total 33125
telemt_desync_full_logged_total 10001
telemt_desync_suppressed_total 23124
telemt_desync_frames_bucket_total{bucket="1_2"} 7228
telemt_desync_frames_bucket_total{bucket="3_10"} 14706
telemt_desync_frames_bucket_total{bucket="gt_10"} 11191
telemt_pool_swap_total 123
telemt_pool_force_close_total 3948
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 871
telemt_me_draining_writers_reap_progress_total 37483
telemt_me_writer_removed_unexpected_total 2368
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5083
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34517
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3389
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 559
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33535
telemt_me_writer_teardown_success_total{mode="normal"} 39600
telemt_me_writer_teardown_noop_total 37510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 72582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 77006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 77091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 77093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 77096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 77101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 77101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 77105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 77110
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 219.141048
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 77110
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 871
telemt_me_refill_failed_total 3814
telemt_me_writer_restored_same_endpoint_total 1728
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 618
telemt_user_connections_total{user="hello"} 17288604
telemt_user_connections_current{user="hello"} 3729
telemt_user_octets_from_client{user="hello"} 253558176137 (236.14 GB)
telemt_user_octets_to_client{user="hello"} 1336931132739 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 409002
telemt_user_msgs_to_client{user="hello"} 794272
telemt_user_unique_ips_current{user="hello"} 1459
telemt_user_unique_ips_recent_window{user="hello"} 703
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 119007.2 (33h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6448410
telemt_connections_bad_total 613639
telemt_connections_current 1934
telemt_connections_me_current 1934
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 136067
telemt_upstream_connect_attempt_total 63298
telemt_upstream_connect_success_total 62561
telemt_upstream_connect_fail_total 631
telemt_upstream_connect_attempts_per_request{bucket="1"} 63192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 361
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 631
telemt_me_reconnect_attempts_total 69939
telemt_me_reconnect_success_total 1893
telemt_me_reader_eof_total 1667
telemt_me_idle_close_by_peer_total 1666
telemt_me_route_drop_no_conn_total 2483015
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5018724
telemt_me_endpoint_quarantine_total 807
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 905
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 25006
telemt_desync_full_logged_total 8758
telemt_desync_suppressed_total 16248
telemt_desync_frames_bucket_total{bucket="1_2"} 4947
telemt_desync_frames_bucket_total{bucket="3_10"} 9654
telemt_desync_frames_bucket_total{bucket="gt_10"} 10405
telemt_pool_swap_total 124
telemt_pool_force_close_total 3550
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 418
telemt_me_draining_writers_reap_progress_total 42020
telemt_me_writer_removed_unexpected_total 1702
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4246
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39509
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3144
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38470
telemt_me_writer_teardown_success_total{mode="normal"} 43755
telemt_me_writer_teardown_noop_total 42021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85773
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85776
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.585575
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85776
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 418
telemt_me_refill_failed_total 4215
telemt_me_writer_restored_same_endpoint_total 1580
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 5010720
telemt_user_connections_current{user="hello"} 1934
telemt_user_octets_from_client{user="hello"} 129853290720 (120.94 GB)
telemt_user_octets_to_client{user="hello"} 2085036168078 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 742
telemt_user_unique_ips_recent_window{user="hello"} 692
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 55843.2 (15h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4472183
telemt_connections_bad_total 183980
telemt_connections_current 2931
telemt_connections_me_current 2931
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1768569
telemt_upstream_connect_attempt_total 32083
telemt_upstream_connect_success_total 31869
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 32075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12431
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_reconnect_attempts_total 46101
telemt_me_reconnect_success_total 1036
telemt_me_reader_eof_total 727
telemt_me_idle_close_by_peer_total 727
telemt_me_route_drop_no_conn_total 1121254
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2214618
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 431
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_me_writers_warm_current 6
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 11922
telemt_desync_full_logged_total 4095
telemt_desync_suppressed_total 7827
telemt_desync_frames_bucket_total{bucket="1_2"} 2291
telemt_desync_frames_bucket_total{bucket="3_10"} 4566
telemt_desync_frames_bucket_total{bucket="gt_10"} 5065
telemt_pool_swap_total 60
telemt_pool_force_close_total 1761
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 20677
telemt_me_writer_removed_unexpected_total 797
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1759
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19745
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1552
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 209
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18916
telemt_me_writer_teardown_success_total{mode="normal"} 21504
telemt_me_writer_teardown_noop_total 20679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42077
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42183
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.700028
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42183
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 2618
telemt_me_writer_restored_same_endpoint_total 924
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2216974
telemt_user_connections_current{user="hello"} 2931
telemt_user_octets_from_client{user="hello"} 59239004876 (55.17 GB)
telemt_user_octets_to_client{user="hello"} 975852358306 (908.83 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1275
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 36814.1 (10h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262769
telemt_connections_bad_total 1964
telemt_connections_current 487
telemt_connections_me_current 487
telemt_handshake_timeouts_total 6725
telemt_upstream_connect_attempt_total 17754
telemt_upstream_connect_success_total 17710
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 17750
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 96
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_reconnect_attempts_total 424
telemt_me_reconnect_success_total 245
telemt_me_reader_eof_total 245
telemt_me_idle_close_by_peer_total 245
telemt_me_route_drop_no_conn_total 74152
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 234660
telemt_me_endpoint_quarantine_total 351
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 318
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 5
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
telemt_desync_total 1233
telemt_desync_full_logged_total 337
telemt_desync_suppressed_total 896
telemt_desync_frames_bucket_total{bucket="1_2"} 429
telemt_desync_frames_bucket_total{bucket="3_10"} 475
telemt_desync_frames_bucket_total{bucket="gt_10"} 329
telemt_pool_swap_total 40
telemt_pool_force_close_total 891
telemt_me_writer_close_signal_drop_total 34
telemt_me_draining_writers_reap_progress_total 16068
telemt_me_writer_removed_unexpected_total 234
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1022
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15291
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 889
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15177
telemt_me_writer_teardown_success_total{mode="normal"} 16313
telemt_me_writer_teardown_noop_total 16068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32353
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32381
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.262018
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32381
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 34
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 213
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 234289
telemt_user_connections_current{user="hello"} 487
telemt_user_octets_from_client{user="hello"} 3956486320 (3.68 GB)
telemt_user_octets_to_client{user="hello"} 144211960068 (134.31 GB)
telemt_user_unique_ips_current{user="hello"} 208
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 119011.6 (33h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7810137
telemt_connections_bad_total 775509
telemt_connections_current 2439
telemt_connections_me_current 2439
telemt_handshake_timeouts_total 222607
telemt_upstream_connect_attempt_total 46897
telemt_upstream_connect_success_total 46726
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 46860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23573
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_reconnect_attempts_total 1698
telemt_me_reconnect_success_total 914
telemt_me_reader_eof_total 908
telemt_me_idle_close_by_peer_total 908
telemt_me_route_drop_no_conn_total 2216531
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5828816
telemt_me_endpoint_quarantine_total 850
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 912
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_me_writers_active_current 43
telemt_desync_total 22741
telemt_desync_full_logged_total 7502
telemt_desync_suppressed_total 15239
telemt_desync_frames_bucket_total{bucket="1_2"} 5695
telemt_desync_frames_bucket_total{bucket="3_10"} 8251
telemt_desync_frames_bucket_total{bucket="gt_10"} 8795
telemt_pool_swap_total 132
telemt_pool_force_close_total 3517
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 414
telemt_me_draining_writers_reap_progress_total 42328
telemt_me_writer_removed_unexpected_total 871
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3309
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39917
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3429
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38811
telemt_me_writer_teardown_success_total{mode="normal"} 43226
telemt_me_writer_teardown_noop_total 42330
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85076
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85556
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.014121
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85556
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 414
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 818
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 45
telemt_user_connections_total{user="hello"} 5803313
telemt_user_connections_current{user="hello"} 2439
telemt_user_octets_from_client{user="hello"} 114546561308 (106.68 GB)
telemt_user_octets_to_client{user="hello"} 2715201784996 (2.47 TB)
telemt_user_unique_ips_current{user="hello"} 891
telemt_user_unique_ips_recent_window{user="hello"} 810
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 119008.3 (33h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6795948
telemt_connections_bad_total 663806
telemt_connections_current 3731
telemt_connections_me_current 3731
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 183655
telemt_upstream_connect_attempt_total 62753
telemt_upstream_connect_success_total 62279
telemt_upstream_connect_fail_total 414
telemt_upstream_connect_attempts_per_request{bucket="1"} 62693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35946
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 414
telemt_me_reconnect_attempts_total 5809
telemt_me_reconnect_success_total 1290
telemt_me_reader_eof_total 1156
telemt_me_idle_close_by_peer_total 1156
telemt_me_seq_mismatch_total 56
telemt_me_route_drop_no_conn_total 2273262
telemt_me_route_drop_channel_closed_total 191
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5196757
telemt_me_endpoint_quarantine_total 941
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 914
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 21646
telemt_desync_full_logged_total 7213
telemt_desync_suppressed_total 14433
telemt_desync_frames_bucket_total{bucket="1_2"} 5435
telemt_desync_frames_bucket_total{bucket="3_10"} 7916
telemt_desync_frames_bucket_total{bucket="gt_10"} 8295
telemt_pool_swap_total 130
telemt_pool_force_close_total 3433
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 415
telemt_me_draining_writers_reap_progress_total 40879
telemt_me_writer_removed_unexpected_total 1169
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3863
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38243
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37446
telemt_me_writer_teardown_success_total{mode="normal"} 42106
telemt_me_writer_teardown_noop_total 40883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82989
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.704753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82989
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 415
telemt_me_refill_failed_total 260
telemt_me_writer_restored_same_endpoint_total 1007
telemt_me_writer_restored_fallback_total 74
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 5199347
telemt_user_connections_current{user="hello"} 3731
telemt_user_octets_from_client{user="hello"} 97399126513 (90.71 GB)
telemt_user_octets_to_client{user="hello"} 2254546827760 (2.05 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1486
telemt_user_unique_ips_recent_window{user="hello"} 654
```