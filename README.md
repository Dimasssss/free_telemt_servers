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

# Server Metrics 2026-03-22 08:18:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 40316.1 (11h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 937220
telemt_connections_bad_total 55474
telemt_connections_current 1584
telemt_connections_me_current 1584
telemt_handshake_timeouts_total 43457
telemt_upstream_connect_attempt_total 16110
telemt_upstream_connect_success_total 16109
telemt_upstream_connect_attempts_per_request{bucket="1"} 16109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 477
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 249
telemt_me_idle_close_by_peer_total 249
telemt_me_route_drop_no_conn_total 538791
telemt_me_route_drop_channel_closed_total 164
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 779923
telemt_me_endpoint_quarantine_total 287
telemt_me_single_endpoint_shadow_rotate_total 325
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 46
telemt_desync_total 5851
telemt_desync_full_logged_total 1645
telemt_desync_suppressed_total 4206
telemt_desync_frames_bucket_total{bucket="1_2"} 1810
telemt_desync_frames_bucket_total{bucket="3_10"} 2203
telemt_desync_frames_bucket_total{bucket="gt_10"} 1838
telemt_pool_swap_total 44
telemt_pool_force_close_total 1236
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 138
telemt_me_draining_writers_reap_progress_total 14625
telemt_me_writer_removed_unexpected_total 246
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1007
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13815
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1214
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13389
telemt_me_writer_teardown_success_total{mode="normal"} 14822
telemt_me_writer_teardown_noop_total 14627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 26998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29449
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.731993
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29449
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 138
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 229
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 778441
telemt_user_connections_current{user="hello"} 1584
telemt_user_octets_from_client{user="hello"} 10557353656 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 251557175720 (234.28 GB)
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 53682.2 (14h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1416854
telemt_connections_bad_total 140666
telemt_connections_current 2223
telemt_connections_me_current 2223
telemt_handshake_timeouts_total 41701
telemt_upstream_connect_attempt_total 28118
telemt_upstream_connect_success_total 27699
telemt_upstream_connect_fail_total 367
telemt_upstream_connect_attempts_per_request{bucket="1"} 28066
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13651
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 367
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2327
telemt_me_reconnect_success_total 1025
telemt_me_reader_eof_total 926
telemt_me_idle_close_by_peer_total 926
telemt_me_route_drop_no_conn_total 593390
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1069320
telemt_me_endpoint_quarantine_total 477
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 427
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 128
telemt_desync_total 4711
telemt_desync_full_logged_total 2736
telemt_desync_suppressed_total 1975
telemt_desync_frames_bucket_total{bucket="1_2"} 1020
telemt_desync_frames_bucket_total{bucket="3_10"} 1826
telemt_desync_frames_bucket_total{bucket="gt_10"} 1865
telemt_pool_swap_total 55
telemt_pool_force_close_total 1480
telemt_me_writer_close_signal_drop_total 126
telemt_me_draining_writers_reap_progress_total 21859
telemt_me_writer_removed_unexpected_total 898
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2131
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20613
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1407
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 73
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20379
telemt_me_writer_teardown_success_total{mode="normal"} 22744
telemt_me_writer_teardown_noop_total 21859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43724
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44439
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44603
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.943677
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44603
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 126
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 827
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 1070962
telemt_user_connections_current{user="hello"} 2223
telemt_user_octets_from_client{user="hello"} 16603713898 (15.46 GB)
telemt_user_octets_to_client{user="hello"} 379319689771 (353.27 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 1292
telemt_user_unique_ips_recent_window{user="hello"} 455
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 128544.0 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9529276
telemt_connections_bad_total 855137
telemt_connections_current 4848
telemt_connections_me_current 4848
telemt_handshake_timeouts_total 289007
telemt_upstream_connect_attempt_total 47425
telemt_upstream_connect_success_total 47345
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 47353
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21364
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25785
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1886
telemt_me_reconnect_success_total 976
telemt_me_reader_eof_total 981
telemt_me_idle_close_by_peer_total 981
telemt_me_route_drop_no_conn_total 5263447
telemt_me_route_drop_channel_closed_total 79
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7477275
telemt_me_endpoint_quarantine_total 803
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 964
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_me_writers_active_current 86
telemt_desync_total 32546
telemt_desync_full_logged_total 10715
telemt_desync_suppressed_total 21831
telemt_desync_frames_bucket_total{bucket="1_2"} 7127
telemt_desync_frames_bucket_total{bucket="3_10"} 12618
telemt_desync_frames_bucket_total{bucket="gt_10"} 12801
telemt_pool_swap_total 138
telemt_pool_force_close_total 4564
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 692
telemt_me_draining_writers_reap_progress_total 43244
telemt_me_writer_removed_unexpected_total 946
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3620
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40048
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4287
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 277
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38680
telemt_me_writer_teardown_success_total{mode="normal"} 43668
telemt_me_writer_teardown_noop_total 43288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85986
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86956
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 182.351696
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86956
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 692
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 874
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 7467675
telemt_user_connections_current{user="hello"} 4848
telemt_user_octets_from_client{user="hello"} 124216857000 (115.69 GB)
telemt_user_octets_to_client{user="hello"} 2514536993580 (2.29 TB)
telemt_user_unique_ips_current{user="hello"} 1916
telemt_user_unique_ips_recent_window{user="hello"} 629
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 128543.3 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7802205
telemt_connections_bad_total 691716
telemt_connections_current 4203
telemt_connections_me_current 4203
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 252641
telemt_upstream_connect_attempt_total 53490
telemt_upstream_connect_success_total 53016
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 53258
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25856
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2812
telemt_me_reconnect_success_total 1060
telemt_me_reader_eof_total 982
telemt_me_idle_close_by_peer_total 982
telemt_me_route_drop_no_conn_total 2618790
telemt_me_route_drop_channel_closed_total 314
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5776039
telemt_me_endpoint_quarantine_total 813
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 991
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 26431
telemt_desync_full_logged_total 9042
telemt_desync_suppressed_total 17389
telemt_desync_frames_bucket_total{bucket="1_2"} 6342
telemt_desync_frames_bucket_total{bucket="3_10"} 10238
telemt_desync_frames_bucket_total{bucket="gt_10"} 9851
telemt_pool_swap_total 140
telemt_pool_force_close_total 4180
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 446
telemt_me_draining_writers_reap_progress_total 41562
telemt_me_writer_removed_unexpected_total 1004
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3529
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38949
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 245
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37382
telemt_me_writer_teardown_success_total{mode="normal"} 42478
telemt_me_writer_teardown_noop_total 41568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84046
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 56.954169
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84046
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 446
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 899
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 5698808
telemt_user_connections_current{user="hello"} 4203
telemt_user_octets_from_client{user="hello"} 158534171031 (147.65 GB)
telemt_user_octets_to_client{user="hello"} 2739390652158 (2.49 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1619
telemt_user_unique_ips_recent_window{user="hello"} 574
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 128507.8 (35h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7522619
telemt_connections_bad_total 622514
telemt_connections_current 3862
telemt_connections_me_current 3862
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 248723
telemt_upstream_connect_attempt_total 57911
telemt_upstream_connect_success_total 57237
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 57384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26861
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1303
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2786
telemt_me_reconnect_success_total 1215
telemt_me_reader_eof_total 1113
telemt_me_idle_close_by_peer_total 1113
telemt_me_route_drop_no_conn_total 3028537
telemt_me_route_drop_channel_closed_total 182
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5608959
telemt_me_endpoint_quarantine_total 906
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 949
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_desync_total 26276
telemt_desync_full_logged_total 8947
telemt_desync_suppressed_total 17329
telemt_desync_frames_bucket_total{bucket="1_2"} 6333
telemt_desync_frames_bucket_total{bucket="3_10"} 10086
telemt_desync_frames_bucket_total{bucket="gt_10"} 9857
telemt_pool_swap_total 137
telemt_pool_force_close_total 4078
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 473
telemt_me_draining_writers_reap_progress_total 42573
telemt_me_writer_removed_unexpected_total 1123
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3785
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39895
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3771
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 307
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38495
telemt_me_writer_teardown_success_total{mode="normal"} 43680
telemt_me_writer_teardown_noop_total 42585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85150
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86115
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86263
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86265
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 45.391575
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86265
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 473
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 1052
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 65
telemt_user_connections_total{user="hello"} 5602097
telemt_user_connections_current{user="hello"} 3862
telemt_user_octets_from_client{user="hello"} 146305035199 (136.26 GB)
telemt_user_octets_to_client{user="hello"} 2492310436903 (2.27 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1538
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 128546.9 (35h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24197772
telemt_connections_bad_total 1979760
telemt_connections_current 5784
telemt_connections_me_current 5784
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 697840
telemt_upstream_connect_attempt_total 241509
telemt_upstream_connect_success_total 221750
telemt_upstream_connect_fail_total 17759
telemt_upstream_connect_attempts_per_request{bucket="1"} 239509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155303
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52548
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17759
telemt_me_keepalive_timeout_total 455
telemt_me_reconnect_attempts_total 66525
telemt_me_reconnect_success_total 2701
telemt_me_reader_eof_total 1682
telemt_me_idle_close_by_peer_total 1680
telemt_me_route_drop_no_conn_total 47030804
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19572348
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 994
telemt_me_single_endpoint_outage_enter_total 164
telemt_me_single_endpoint_outage_exit_total 164
telemt_me_single_endpoint_outage_reconnect_attempt_total 335
telemt_me_single_endpoint_outage_reconnect_success_total 86
telemt_me_single_endpoint_quarantine_bypass_total 335
telemt_me_single_endpoint_shadow_rotate_total 1008
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 72
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
telemt_me_writers_active_current 46
telemt_desync_total 38013
telemt_desync_full_logged_total 11216
telemt_desync_suppressed_total 26797
telemt_desync_frames_bucket_total{bucket="1_2"} 8427
telemt_desync_frames_bucket_total{bucket="3_10"} 16788
telemt_desync_frames_bucket_total{bucket="gt_10"} 12798
telemt_pool_swap_total 133
telemt_pool_force_close_total 4217
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 973
telemt_me_draining_writers_reap_progress_total 39989
telemt_me_writer_removed_unexpected_total 2504
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5408
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36810
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3622
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 595
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35772
telemt_me_writer_teardown_success_total{mode="normal"} 42218
telemt_me_writer_teardown_noop_total 40021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78789
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82223
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82239
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 284.441572
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82239
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 973
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1829
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14757
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 19737771
telemt_user_connections_current{user="hello"} 5784
telemt_user_octets_from_client{user="hello"} 278076828439 (258.98 GB)
telemt_user_octets_to_client{user="hello"} 1439902364103 (1.31 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2100
telemt_user_unique_ips_recent_window{user="hello"} 1242
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 128514.0 (35h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7150395
telemt_connections_bad_total 646551
telemt_connections_current 4274
telemt_connections_me_current 4274
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 147032
telemt_upstream_connect_attempt_total 66364
telemt_upstream_connect_success_total 65578
telemt_upstream_connect_fail_total 669
telemt_upstream_connect_attempts_per_request{bucket="1"} 66247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37416
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27794
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 669
telemt_me_reconnect_attempts_total 70259
telemt_me_reconnect_success_total 1986
telemt_me_reader_eof_total 1746
telemt_me_idle_close_by_peer_total 1745
telemt_me_route_drop_no_conn_total 2776389
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5616496
telemt_me_endpoint_quarantine_total 866
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 975
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 28262
telemt_desync_full_logged_total 9848
telemt_desync_suppressed_total 18414
telemt_desync_frames_bucket_total{bucket="1_2"} 5651
telemt_desync_frames_bucket_total{bucket="3_10"} 10874
telemt_desync_frames_bucket_total{bucket="gt_10"} 11737
telemt_pool_swap_total 134
telemt_pool_force_close_total 3863
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 457
telemt_me_draining_writers_reap_progress_total 44737
telemt_me_writer_removed_unexpected_total 1777
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4495
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42044
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3435
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 428
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40874
telemt_me_writer_teardown_success_total{mode="normal"} 46539
telemt_me_writer_teardown_noop_total 44738
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91277
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.240066
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91277
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 457
telemt_me_refill_failed_total 4226
telemt_me_writer_restored_same_endpoint_total 1648
telemt_me_writer_restored_fallback_total 40
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 5607173
telemt_user_connections_current{user="hello"} 4274
telemt_user_octets_from_client{user="hello"} 141802960452 (132.06 GB)
telemt_user_octets_to_client{user="hello"} 2333418994338 (2.12 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1661
telemt_user_unique_ips_recent_window{user="hello"} 558
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 65349.9 (18h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5539490
telemt_connections_bad_total 218487
telemt_connections_current 4091
telemt_connections_me_current 4091
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2198962
telemt_upstream_connect_attempt_total 35470
telemt_upstream_connect_success_total 35220
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 35463
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14147
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_reconnect_attempts_total 46411
telemt_me_reconnect_success_total 1153
telemt_me_reader_eof_total 836
telemt_me_idle_close_by_peer_total 836
telemt_me_route_drop_no_conn_total 1378584
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2774805
telemt_me_endpoint_quarantine_total 453
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 500
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
telemt_me_writers_active_current 47
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 14931
telemt_desync_full_logged_total 5110
telemt_desync_suppressed_total 9821
telemt_desync_frames_bucket_total{bucket="1_2"} 2913
telemt_desync_frames_bucket_total{bucket="3_10"} 5740
telemt_desync_frames_bucket_total{bucket="gt_10"} 6278
telemt_pool_swap_total 70
telemt_pool_force_close_total 2085
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 197
telemt_me_draining_writers_reap_progress_total 23681
telemt_me_writer_removed_unexpected_total 906
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2039
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22570
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1820
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21596
telemt_me_writer_teardown_success_total{mode="normal"} 24609
telemt_me_writer_teardown_noop_total 23687
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48296
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.435674
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48296
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 197
telemt_me_refill_failed_total 2629
telemt_me_writer_restored_same_endpoint_total 1030
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4274
telemt_user_connections_total{user="hello"} 2776086
telemt_user_connections_current{user="hello"} 4091
telemt_user_octets_from_client{user="hello"} 70895428776 (66.03 GB)
telemt_user_octets_to_client{user="hello"} 1222507483182 (1.11 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1593
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 46320.9 (12h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 394783
telemt_connections_bad_total 2754
telemt_connections_current 1029
telemt_connections_me_current 1029
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8099
telemt_upstream_connect_attempt_total 24704
telemt_upstream_connect_success_total 24648
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 24700
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 230
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 964
telemt_me_reconnect_success_total 340
telemt_me_reader_eof_total 333
telemt_me_idle_close_by_peer_total 333
telemt_me_route_drop_no_conn_total 122115
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356478
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 401
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_writers_active_current 48
telemt_desync_total 1625
telemt_desync_full_logged_total 471
telemt_desync_suppressed_total 1154
telemt_desync_frames_bucket_total{bucket="1_2"} 494
telemt_desync_frames_bucket_total{bucket="3_10"} 636
telemt_desync_frames_bucket_total{bucket="gt_10"} 495
telemt_pool_swap_total 51
telemt_pool_force_close_total 1142
telemt_me_writer_close_signal_drop_total 42
telemt_me_draining_writers_reap_progress_total 19780
telemt_me_writer_removed_unexpected_total 318
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1356
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18757
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18638
telemt_me_writer_teardown_success_total{mode="normal"} 20113
telemt_me_writer_teardown_noop_total 19780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 39893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 39893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 39893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 39893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 39893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 39893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 39893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 39893
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 39893
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.816434
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 39893
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 42
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 289
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 358673
telemt_user_connections_current{user="hello"} 1029
telemt_user_octets_from_client{user="hello"} 6799534873 (6.33 GB)
telemt_user_octets_to_client{user="hello"} 188559576003 (175.61 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 329
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 128518.5 (35h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8791420
telemt_connections_bad_total 993519
telemt_connections_current 4781
telemt_connections_me_current 4781
telemt_handshake_timeouts_total 244871
telemt_upstream_connect_attempt_total 50082
telemt_upstream_connect_success_total 49893
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 50038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24703
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_reconnect_attempts_total 1874
telemt_me_reconnect_success_total 1023
telemt_me_reader_eof_total 993
telemt_me_idle_close_by_peer_total 993
telemt_me_route_drop_no_conn_total 2457897
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6519065
telemt_me_endpoint_quarantine_total 914
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 977
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 26044
telemt_desync_full_logged_total 8568
telemt_desync_suppressed_total 17476
telemt_desync_frames_bucket_total{bucket="1_2"} 6437
telemt_desync_frames_bucket_total{bucket="3_10"} 9463
telemt_desync_frames_bucket_total{bucket="gt_10"} 10144
telemt_pool_swap_total 142
telemt_pool_force_close_total 3809
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 460
telemt_me_draining_writers_reap_progress_total 45203
telemt_me_writer_removed_unexpected_total 954
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3598
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42588
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3711
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 98
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41394
telemt_me_writer_teardown_success_total{mode="normal"} 46186
telemt_me_writer_teardown_noop_total 45205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 90891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91391
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91391
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.691374
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91391
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 460
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 895
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 50
telemt_user_connections_total{user="hello"} 6492300
telemt_user_connections_current{user="hello"} 4781
telemt_user_octets_from_client{user="hello"} 127135009108 (118.40 GB)
telemt_user_octets_to_client{user="hello"} 3050773593788 (2.77 TB)
telemt_user_unique_ips_current{user="hello"} 1771
telemt_user_unique_ips_recent_window{user="hello"} 687
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 128515.1 (35h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7660125
telemt_connections_bad_total 842392
telemt_connections_current 4184
telemt_connections_me_current 4184
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 205312
telemt_upstream_connect_attempt_total 66116
telemt_upstream_connect_success_total 65605
telemt_upstream_connect_fail_total 445
telemt_upstream_connect_attempts_per_request{bucket="1"} 66050
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37615
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26846
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 626
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 445
telemt_me_reconnect_attempts_total 6340
telemt_me_reconnect_success_total 1431
telemt_me_reader_eof_total 1285
telemt_me_idle_close_by_peer_total 1285
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2580373
telemt_me_route_drop_channel_closed_total 216
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5828094
telemt_me_endpoint_quarantine_total 1006
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 975
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 25010
telemt_desync_full_logged_total 8315
telemt_desync_suppressed_total 16695
telemt_desync_frames_bucket_total{bucket="1_2"} 6175
telemt_desync_frames_bucket_total{bucket="3_10"} 9196
telemt_desync_frames_bucket_total{bucket="gt_10"} 9639
telemt_pool_swap_total 139
telemt_pool_force_close_total 3756
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 455
telemt_me_draining_writers_reap_progress_total 43860
telemt_me_writer_removed_unexpected_total 1299
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4182
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41039
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3491
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40104
telemt_me_writer_teardown_success_total{mode="normal"} 45221
telemt_me_writer_teardown_noop_total 43864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89047
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89085
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89085
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.732994
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89085
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 455
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 1118
telemt_me_writer_restored_fallback_total 84
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 5829210
telemt_user_connections_current{user="hello"} 4184
telemt_user_octets_from_client{user="hello"} 106957749553 (99.61 GB)
telemt_user_octets_to_client{user="hello"} 2525882832636 (2.30 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1726
telemt_user_unique_ips_recent_window{user="hello"} 578
```