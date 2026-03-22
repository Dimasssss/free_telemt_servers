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

# Server Metrics 2026-03-22 06:56:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 35405.8 (9h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 699898
telemt_connections_bad_total 43236
telemt_connections_current 1349
telemt_connections_me_current 1349
telemt_handshake_timeouts_total 33821
telemt_upstream_connect_attempt_total 14454
telemt_upstream_connect_success_total 14453
telemt_upstream_connect_attempts_per_request{bucket="1"} 14453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9395
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 377
telemt_me_reconnect_success_total 226
telemt_me_reader_eof_total 222
telemt_me_idle_close_by_peer_total 222
telemt_me_route_drop_no_conn_total 249384
telemt_me_route_drop_channel_closed_total 88
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580267
telemt_me_endpoint_quarantine_total 262
telemt_me_single_endpoint_shadow_rotate_total 293
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
telemt_me_writers_active_current 44
telemt_desync_total 4767
telemt_desync_full_logged_total 1336
telemt_desync_suppressed_total 3431
telemt_desync_frames_bucket_total{bucket="1_2"} 1554
telemt_desync_frames_bucket_total{bucket="3_10"} 1782
telemt_desync_frames_bucket_total{bucket="gt_10"} 1431
telemt_pool_swap_total 39
telemt_pool_force_close_total 1048
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 13091
telemt_me_writer_removed_unexpected_total 219
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 909
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12388
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1037
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12043
telemt_me_writer_teardown_success_total{mode="normal"} 13297
telemt_me_writer_teardown_noop_total 13092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25337
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 26379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 26389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 26389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 26389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 26389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 26389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 26389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 26389
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.375287
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 26389
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 8
telemt_me_writer_restored_same_endpoint_total 207
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 579113
telemt_user_connections_current{user="hello"} 1349
telemt_user_octets_from_client{user="hello"} 8104737008 (7.55 GB)
telemt_user_octets_to_client{user="hello"} 202349436392 (188.45 GB)
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 48772.1 (13h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1178310
telemt_connections_bad_total 116405
telemt_connections_current 1334
telemt_connections_me_current 1334
telemt_handshake_timeouts_total 37418
telemt_upstream_connect_attempt_total 25857
telemt_upstream_connect_success_total 25474
telemt_upstream_connect_fail_total 332
telemt_upstream_connect_attempts_per_request{bucket="1"} 25806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12998
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12421
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 332
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1921
telemt_me_reconnect_success_total 759
telemt_me_reader_eof_total 663
telemt_me_idle_close_by_peer_total 663
telemt_me_route_drop_no_conn_total 431786
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 889015
telemt_me_endpoint_quarantine_total 444
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 390
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 3777
telemt_desync_full_logged_total 2209
telemt_desync_suppressed_total 1568
telemt_desync_frames_bucket_total{bucket="1_2"} 793
telemt_desync_frames_bucket_total{bucket="3_10"} 1463
telemt_desync_frames_bucket_total{bucket="gt_10"} 1521
telemt_pool_swap_total 52
telemt_pool_force_close_total 1359
telemt_me_writer_close_signal_drop_total 110
telemt_me_draining_writers_reap_progress_total 20092
telemt_me_writer_removed_unexpected_total 638
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1773
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18941
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1293
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 66
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18733
telemt_me_writer_teardown_success_total{mode="normal"} 20714
telemt_me_writer_teardown_noop_total 20092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40792
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40806
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.146343
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40806
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 110
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 574
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 890825
telemt_user_connections_current{user="hello"} 1334
telemt_user_octets_from_client{user="hello"} 14347940746 (13.36 GB)
telemt_user_octets_to_client{user="hello"} 331305629663 (308.55 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 821
telemt_user_unique_ips_recent_window{user="hello"} 395
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 123631.9 (34h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8830970
telemt_connections_bad_total 819053
telemt_connections_current 3671
telemt_connections_me_current 3671
telemt_handshake_timeouts_total 278289
telemt_upstream_connect_attempt_total 45793
telemt_upstream_connect_success_total 45715
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 45723
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 187
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1748
telemt_me_reconnect_success_total 911
telemt_me_reader_eof_total 913
telemt_me_idle_close_by_peer_total 913
telemt_me_route_drop_no_conn_total 4807377
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6972347
telemt_me_endpoint_quarantine_total 788
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 930
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
telemt_me_writers_active_current 46
telemt_desync_total 29907
telemt_desync_full_logged_total 9905
telemt_desync_suppressed_total 20002
telemt_desync_frames_bucket_total{bucket="1_2"} 6481
telemt_desync_frames_bucket_total{bucket="3_10"} 11653
telemt_desync_frames_bucket_total{bucket="gt_10"} 11773
telemt_pool_swap_total 134
telemt_pool_force_close_total 4425
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 670
telemt_me_draining_writers_reap_progress_total 41801
telemt_me_writer_removed_unexpected_total 878
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3476
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38702
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4160
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 265
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37376
telemt_me_writer_teardown_success_total{mode="normal"} 42178
telemt_me_writer_teardown_noop_total 41845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84023
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 176.406471
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84023
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 670
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 812
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 6963228
telemt_user_connections_current{user="hello"} 3671
telemt_user_octets_from_client{user="hello"} 117834444260 (109.74 GB)
telemt_user_octets_to_client{user="hello"} 2381969808504 (2.17 TB)
telemt_user_unique_ips_current{user="hello"} 1500
telemt_user_unique_ips_recent_window{user="hello"} 553
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 123633.4 (34h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7276537
telemt_connections_bad_total 642290
telemt_connections_current 3886
telemt_connections_me_current 3886
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 240244
telemt_upstream_connect_attempt_total 49801
telemt_upstream_connect_success_total 49395
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49604
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24374
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24429
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2623
telemt_me_reconnect_success_total 982
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 948
telemt_me_route_drop_no_conn_total 2447537
telemt_me_route_drop_channel_closed_total 299
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5386826
telemt_me_endpoint_quarantine_total 785
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 951
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
telemt_me_writers_active_current 46
telemt_desync_total 24846
telemt_desync_full_logged_total 8539
telemt_desync_suppressed_total 16307
telemt_desync_frames_bucket_total{bucket="1_2"} 5944
telemt_desync_frames_bucket_total{bucket="3_10"} 9653
telemt_desync_frames_bucket_total{bucket="gt_10"} 9249
telemt_pool_swap_total 135
telemt_pool_force_close_total 4026
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 417
telemt_me_draining_writers_reap_progress_total 40263
telemt_me_writer_removed_unexpected_total 925
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3339
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37778
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3793
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 233
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36237
telemt_me_writer_teardown_success_total{mode="normal"} 41117
telemt_me_writer_teardown_noop_total 40269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81386
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.863390
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81386
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 417
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 858
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 5307942
telemt_user_connections_current{user="hello"} 3886
telemt_user_octets_from_client{user="hello"} 151712338161 (141.29 GB)
telemt_user_octets_to_client{user="hello"} 2568076317455 (2.34 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1499
telemt_user_unique_ips_recent_window{user="hello"} 509
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 123597.4 (34h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7014315
telemt_connections_bad_total 584271
telemt_connections_current 3299
telemt_connections_me_current 3299
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 235176
telemt_upstream_connect_attempt_total 56223
telemt_upstream_connect_success_total 55601
telemt_upstream_connect_fail_total 145
telemt_upstream_connect_attempts_per_request{bucket="1"} 55746
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27537
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25971
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 843
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1250
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 145
telemt_me_keepalive_timeout_total 104
telemt_me_reconnect_attempts_total 2650
telemt_me_reconnect_success_total 1126
telemt_me_reader_eof_total 1050
telemt_me_idle_close_by_peer_total 1050
telemt_me_route_drop_no_conn_total 2556241
telemt_me_route_drop_channel_closed_total 161
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5222260
telemt_me_endpoint_quarantine_total 877
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 919
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 24721
telemt_desync_full_logged_total 8398
telemt_desync_suppressed_total 16323
telemt_desync_frames_bucket_total{bucket="1_2"} 5991
telemt_desync_frames_bucket_total{bucket="3_10"} 9484
telemt_desync_frames_bucket_total{bucket="gt_10"} 9246
telemt_pool_swap_total 133
telemt_pool_force_close_total 3895
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 434
telemt_me_draining_writers_reap_progress_total 41170
telemt_me_writer_removed_unexpected_total 1040
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3595
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38629
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37275
telemt_me_writer_teardown_success_total{mode="normal"} 42224
telemt_me_writer_teardown_noop_total 41182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 81842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83406
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.512270
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83406
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 434
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 970
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 5216052
telemt_user_connections_current{user="hello"} 3299
telemt_user_octets_from_client{user="hello"} 141059446107 (131.37 GB)
telemt_user_octets_to_client{user="hello"} 2365408714819 (2.15 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1297
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 123636.6 (34h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22491240
telemt_connections_bad_total 1898722
telemt_connections_current 5029
telemt_connections_me_current 5029
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 673126
telemt_upstream_connect_attempt_total 238553
telemt_upstream_connect_success_total 218933
telemt_upstream_connect_fail_total 17675
telemt_upstream_connect_attempts_per_request{bucket="1"} 236608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154130
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51292
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11034
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17675
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66389
telemt_me_reconnect_success_total 2618
telemt_me_reader_eof_total 1648
telemt_me_idle_close_by_peer_total 1646
telemt_me_route_drop_no_conn_total 42575706
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18084471
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 967
telemt_me_single_endpoint_outage_enter_total 155
telemt_me_single_endpoint_outage_exit_total 155
telemt_me_single_endpoint_outage_reconnect_attempt_total 324
telemt_me_single_endpoint_outage_reconnect_success_total 81
telemt_me_single_endpoint_quarantine_bypass_total 324
telemt_me_single_endpoint_shadow_rotate_total 970
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
telemt_desync_total 34935
telemt_desync_full_logged_total 10497
telemt_desync_suppressed_total 24438
telemt_desync_frames_bucket_total{bucket="1_2"} 7773
telemt_desync_frames_bucket_total{bucket="3_10"} 15410
telemt_desync_frames_bucket_total{bucket="gt_10"} 11752
telemt_pool_swap_total 128
telemt_pool_force_close_total 4057
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 926
telemt_me_draining_writers_reap_progress_total 38748
telemt_me_writer_removed_unexpected_total 2424
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5244
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35659
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3478
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 579
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34691
telemt_me_writer_teardown_success_total{mode="normal"} 40903
telemt_me_writer_teardown_noop_total 38778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 79545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 79637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 79646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 79654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 79665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 79668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 79676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 79681
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 279.578080
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 79681
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 926
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1781
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 18249230
telemt_user_connections_current{user="hello"} 5029
telemt_user_octets_from_client{user="hello"} 268446627739 (250.01 GB)
telemt_user_octets_to_client{user="hello"} 1388471956250 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 500908
telemt_user_msgs_to_client{user="hello"} 1006528
telemt_user_unique_ips_current{user="hello"} 1890
telemt_user_unique_ips_recent_window{user="hello"} 950
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 123604.2 (34h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6739234
telemt_connections_bad_total 623497
telemt_connections_current 3367
telemt_connections_me_current 3367
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 139728
telemt_upstream_connect_attempt_total 64860
telemt_upstream_connect_success_total 64118
telemt_upstream_connect_fail_total 636
telemt_upstream_connect_attempts_per_request{bucket="1"} 64754
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36748
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27007
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 362
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 636
telemt_me_reconnect_attempts_total 70000
telemt_me_reconnect_success_total 1918
telemt_me_reader_eof_total 1695
telemt_me_idle_close_by_peer_total 1694
telemt_me_route_drop_no_conn_total 2578339
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5265788
telemt_me_endpoint_quarantine_total 830
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 940
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
telemt_me_writers_active_current 47
telemt_desync_total 26375
telemt_desync_full_logged_total 9178
telemt_desync_suppressed_total 17197
telemt_desync_frames_bucket_total{bucket="1_2"} 5277
telemt_desync_frames_bucket_total{bucket="3_10"} 10129
telemt_desync_frames_bucket_total{bucket="gt_10"} 10969
telemt_pool_swap_total 129
telemt_pool_force_close_total 3700
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 435
telemt_me_draining_writers_reap_progress_total 43436
telemt_me_writer_removed_unexpected_total 1726
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4357
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40842
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3290
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 410
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39736
telemt_me_writer_teardown_success_total{mode="normal"} 45199
telemt_me_writer_teardown_noop_total 43437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88636
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.917948
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88636
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 435
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1602
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5257220
telemt_user_connections_current{user="hello"} 3367
telemt_user_octets_from_client{user="hello"} 135062579072 (125.79 GB)
telemt_user_octets_to_client{user="hello"} 2201349498902 (2.00 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1411
telemt_user_unique_ips_recent_window{user="hello"} 660
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 60440.2 (16h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4926746
telemt_connections_bad_total 200778
telemt_connections_current 3149
telemt_connections_me_current 3149
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1950033
telemt_upstream_connect_attempt_total 33690
telemt_upstream_connect_success_total 33459
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 33683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_reconnect_attempts_total 46193
telemt_me_reconnect_success_total 1071
telemt_me_reader_eof_total 761
telemt_me_idle_close_by_peer_total 761
telemt_me_route_drop_no_conn_total 1208268
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2452757
telemt_me_endpoint_quarantine_total 427
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 464
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 13120
telemt_desync_full_logged_total 4527
telemt_desync_suppressed_total 8593
telemt_desync_frames_bucket_total{bucket="1_2"} 2587
telemt_desync_frames_bucket_total{bucket="3_10"} 5003
telemt_desync_frames_bucket_total{bucket="gt_10"} 5530
telemt_pool_swap_total 66
telemt_pool_force_close_total 1914
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 167
telemt_me_draining_writers_reap_progress_total 22084
telemt_me_writer_removed_unexpected_total 831
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1863
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21074
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1691
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20170
telemt_me_writer_teardown_success_total{mode="normal"} 22937
telemt_me_writer_teardown_noop_total 22086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44914
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45023
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.842415
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45023
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 167
telemt_me_refill_failed_total 2621
telemt_me_writer_restored_same_endpoint_total 955
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2454580
telemt_user_connections_current{user="hello"} 3149
telemt_user_octets_from_client{user="hello"} 63607367908 (59.24 GB)
telemt_user_octets_to_client{user="hello"} 1089825336942 (1014.98 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1276
telemt_user_unique_ips_recent_window{user="hello"} 1026
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 41410.9 (11h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 312804
telemt_connections_bad_total 2144
telemt_connections_current 639
telemt_connections_me_current 639
telemt_handshake_timeouts_total 7266
telemt_upstream_connect_attempt_total 19857
telemt_upstream_connect_success_total 19808
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 19853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11376
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_reconnect_attempts_total 835
telemt_me_reconnect_success_total 286
telemt_me_reader_eof_total 281
telemt_me_idle_close_by_peer_total 281
telemt_me_route_drop_no_conn_total 92363
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282617
telemt_me_endpoint_quarantine_total 387
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 357
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
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
telemt_me_writers_active_current 46
telemt_desync_total 1370
telemt_desync_full_logged_total 386
telemt_desync_suppressed_total 984
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 528
telemt_desync_frames_bucket_total{bucket="gt_10"} 381
telemt_pool_swap_total 45
telemt_pool_force_close_total 1009
telemt_me_writer_close_signal_drop_total 36
telemt_me_draining_writers_reap_progress_total 17968
telemt_me_writer_removed_unexpected_total 269
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17088
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1007
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16959
telemt_me_writer_teardown_success_total{mode="normal"} 18249
telemt_me_writer_teardown_noop_total 17968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36217
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36217
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.377797
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36217
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 36
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 245
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 282196
telemt_user_connections_current{user="hello"} 639
telemt_user_octets_from_client{user="hello"} 4730065216 (4.41 GB)
telemt_user_octets_to_client{user="hello"} 160801367084 (149.76 GB)
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 123608.4 (34h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8189911
telemt_connections_bad_total 846161
telemt_connections_current 4115
telemt_connections_me_current 4115
telemt_handshake_timeouts_total 231223
telemt_upstream_connect_attempt_total 48578
telemt_upstream_connect_success_total 48398
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 48539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_reconnect_attempts_total 1790
telemt_me_reconnect_success_total 965
telemt_me_reader_eof_total 947
telemt_me_idle_close_by_peer_total 947
telemt_me_route_drop_no_conn_total 2309904
telemt_me_route_drop_channel_closed_total 54
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6112099
telemt_me_endpoint_quarantine_total 881
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 944
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
telemt_desync_total 24280
telemt_desync_full_logged_total 7987
telemt_desync_suppressed_total 16293
telemt_desync_frames_bucket_total{bucket="1_2"} 6040
telemt_desync_frames_bucket_total{bucket="3_10"} 8864
telemt_desync_frames_bucket_total{bucket="gt_10"} 9376
telemt_pool_swap_total 137
telemt_pool_force_close_total 3658
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 436
telemt_me_draining_writers_reap_progress_total 43861
telemt_me_writer_removed_unexpected_total 910
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3445
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41353
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3566
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 92
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40203
telemt_me_writer_teardown_success_total{mode="normal"} 44798
telemt_me_writer_teardown_noop_total 43863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 88570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 88661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 88661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 88661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 88661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 88661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 88661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 88661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 88661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 88661
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.360946
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 88661
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 436
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 855
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6086051
telemt_user_connections_current{user="hello"} 4116
telemt_user_octets_from_client{user="hello"} 119798507576 (111.57 GB)
telemt_user_octets_to_client{user="hello"} 2851994747144 (2.59 TB)
telemt_user_unique_ips_current{user="hello"} 1538
telemt_user_unique_ips_recent_window{user="hello"} 546
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 123605.1 (34h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7175200
telemt_connections_bad_total 744117
telemt_connections_current 3483
telemt_connections_me_current 3483
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 191798
telemt_upstream_connect_attempt_total 64316
telemt_upstream_connect_success_total 63825
telemt_upstream_connect_fail_total 428
telemt_upstream_connect_attempts_per_request{bucket="1"} 64253
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36675
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26016
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 428
telemt_me_reconnect_attempts_total 5916
telemt_me_reconnect_success_total 1334
telemt_me_reader_eof_total 1194
telemt_me_idle_close_by_peer_total 1194
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2370527
telemt_me_route_drop_channel_closed_total 197
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5472993
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 945
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
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
telemt_me_writers_active_current 42
telemt_desync_total 23161
telemt_desync_full_logged_total 7688
telemt_desync_suppressed_total 15473
telemt_desync_frames_bucket_total{bucket="1_2"} 5739
telemt_desync_frames_bucket_total{bucket="3_10"} 8497
telemt_desync_frames_bucket_total{bucket="gt_10"} 8925
telemt_pool_swap_total 135
telemt_pool_force_close_total 3610
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 436
telemt_me_draining_writers_reap_progress_total 42300
telemt_me_writer_removed_unexpected_total 1209
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3998
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39572
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 232
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38690
telemt_me_writer_teardown_success_total{mode="normal"} 43570
telemt_me_writer_teardown_noop_total 42304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 85874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 85874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 85874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 85874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 85874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 85874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 85874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 85874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 85874
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.428953
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 85874
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 436
telemt_me_refill_failed_total 264
telemt_me_writer_restored_same_endpoint_total 1033
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 5474845
telemt_user_connections_current{user="hello"} 3483
telemt_user_octets_from_client{user="hello"} 101762378113 (94.77 GB)
telemt_user_octets_to_client{user="hello"} 2378677609692 (2.16 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1392
telemt_user_unique_ips_recent_window{user="hello"} 543
```