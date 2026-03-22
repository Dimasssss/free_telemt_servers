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

# Server Metrics 2026-03-22 00:03:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 10598.8 (2h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164297
telemt_connections_bad_total 11308
telemt_connections_current 699
telemt_connections_me_current 699
telemt_handshake_timeouts_total 9185
telemt_upstream_connect_attempt_total 4275
telemt_upstream_connect_success_total 4274
telemt_upstream_connect_attempts_per_request{bucket="1"} 4274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2672
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 104
telemt_me_reconnect_success_total 69
telemt_me_reader_eof_total 70
telemt_me_idle_close_by_peer_total 70
telemt_me_route_drop_no_conn_total 34033
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 134568
telemt_me_endpoint_quarantine_total 69
telemt_me_single_endpoint_shadow_rotate_total 90
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 842
telemt_desync_full_logged_total 258
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 192
telemt_desync_frames_bucket_total{bucket="3_10"} 274
telemt_desync_frames_bucket_total{bucket="gt_10"} 376
telemt_pool_swap_total 11
telemt_pool_force_close_total 299
telemt_me_writer_close_signal_drop_total 19
telemt_me_draining_writers_reap_progress_total 3810
telemt_me_writer_removed_unexpected_total 66
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 279
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3585
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 295
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3511
telemt_me_writer_teardown_success_total{mode="normal"} 3864
telemt_me_writer_teardown_noop_total 3810
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 7570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 7609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 7650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 7672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 7674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 7674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 7674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 7674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 7674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 7674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 7674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 7674
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.330171
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 7674
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 19
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 64
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 134395
telemt_user_connections_current{user="hello"} 699
telemt_user_octets_from_client{user="hello"} 1618891160 (1.51 GB)
telemt_user_octets_to_client{user="hello"} 48438390488 (45.11 GB)
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 74
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 23965.6 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 676006
telemt_connections_bad_total 36040
telemt_connections_current 479
telemt_connections_me_current 479
telemt_handshake_timeouts_total 25721
telemt_upstream_connect_attempt_total 10247
telemt_upstream_connect_success_total 10065
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 10229
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_reconnect_attempts_total 859
telemt_me_reconnect_success_total 312
telemt_me_reader_eof_total 269
telemt_me_idle_close_by_peer_total 269
telemt_me_route_drop_no_conn_total 326792
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 547922
telemt_me_endpoint_quarantine_total 212
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 195
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 2398
telemt_desync_full_logged_total 1374
telemt_desync_suppressed_total 1024
telemt_desync_frames_bucket_total{bucket="1_2"} 513
telemt_desync_frames_bucket_total{bucket="3_10"} 899
telemt_desync_frames_bucket_total{bucket="gt_10"} 986
telemt_pool_swap_total 26
telemt_pool_force_close_total 726
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 9009
telemt_me_writer_removed_unexpected_total 252
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 796
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8469
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 719
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8283
telemt_me_writer_teardown_success_total{mode="normal"} 9265
telemt_me_writer_teardown_noop_total 9009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 17813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18082
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18168
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 18272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 18274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 18274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 18274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 18274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 18274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 18274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 18274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 18274
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.380188
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 18274
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 217
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 547175
telemt_user_connections_current{user="hello"} 479
telemt_user_octets_from_client{user="hello"} 9167340924 (8.54 GB)
telemt_user_octets_to_client{user="hello"} 190504912372 (177.42 GB)
telemt_user_unique_ips_current{user="hello"} 303
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 98825.7 (27h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7455595
telemt_connections_bad_total 592335
telemt_connections_current 1594
telemt_connections_me_current 1594
telemt_handshake_timeouts_total 242143
telemt_upstream_connect_attempt_total 35845
telemt_upstream_connect_success_total 35776
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 35783
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19437
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 155
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1493
telemt_me_reconnect_success_total 746
telemt_me_reader_eof_total 755
telemt_me_idle_close_by_peer_total 755
telemt_me_route_drop_no_conn_total 4500374
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6077467
telemt_me_endpoint_quarantine_total 619
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 735
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
telemt_me_writers_active_current 44
telemt_desync_total 25814
telemt_desync_full_logged_total 8528
telemt_desync_suppressed_total 17286
telemt_desync_frames_bucket_total{bucket="1_2"} 5552
telemt_desync_frames_bucket_total{bucket="3_10"} 10071
telemt_desync_frames_bucket_total{bucket="gt_10"} 10191
telemt_pool_swap_total 106
telemt_pool_force_close_total 3583
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 575
telemt_me_draining_writers_reap_progress_total 32683
telemt_me_writer_removed_unexpected_total 726
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2768
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30199
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3344
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29100
telemt_me_writer_teardown_success_total{mode="normal"} 32967
telemt_me_writer_teardown_noop_total 32727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59786
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64856
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65694
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 153.618515
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65694
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 575
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 666
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6069891
telemt_user_connections_current{user="hello"} 1594
telemt_user_octets_from_client{user="hello"} 104022244456 (96.88 GB)
telemt_user_octets_to_client{user="hello"} 1996534021700 (1.82 TB)
telemt_user_unique_ips_current{user="hello"} 793
telemt_user_unique_ips_recent_window{user="hello"} 172
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 98826.4 (27h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6131792
telemt_connections_bad_total 578416
telemt_connections_current 1569
telemt_connections_me_current 1569
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 202340
telemt_upstream_connect_attempt_total 39749
telemt_upstream_connect_success_total 39407
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 39586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19086
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 28
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 544
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1805
telemt_me_reconnect_success_total 769
telemt_me_reader_eof_total 747
telemt_me_idle_close_by_peer_total 747
telemt_me_route_drop_no_conn_total 2175708
telemt_me_route_drop_channel_closed_total 254
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4594223
telemt_me_endpoint_quarantine_total 605
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 755
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22073
telemt_desync_full_logged_total 7468
telemt_desync_suppressed_total 14605
telemt_desync_frames_bucket_total{bucket="1_2"} 5321
telemt_desync_frames_bucket_total{bucket="3_10"} 8560
telemt_desync_frames_bucket_total{bucket="gt_10"} 8192
telemt_pool_swap_total 108
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 31194
telemt_me_writer_removed_unexpected_total 721
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2642
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29208
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3047
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27948
telemt_me_writer_teardown_success_total{mode="normal"} 31850
telemt_me_writer_teardown_noop_total 31200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 61864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63050
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 47.988464
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63050
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 665
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 4534852
telemt_user_connections_current{user="hello"} 1569
telemt_user_octets_from_client{user="hello"} 138081635373 (128.60 GB)
telemt_user_octets_to_client{user="hello"} 2122422059023 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 707
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 98791.1 (27h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6043686
telemt_connections_bad_total 540265
telemt_connections_current 1612
telemt_connections_me_current 1612
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 193532
telemt_upstream_connect_attempt_total 46213
telemt_upstream_connect_success_total 45903
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 46038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23934
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20561
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 362
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1046
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1808
telemt_me_reconnect_success_total 820
telemt_me_reader_eof_total 769
telemt_me_idle_close_by_peer_total 769
telemt_me_route_drop_no_conn_total 2105409
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4511331
telemt_me_endpoint_quarantine_total 666
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 738
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
telemt_me_writers_active_current 44
telemt_desync_total 21917
telemt_desync_full_logged_total 7304
telemt_desync_suppressed_total 14613
telemt_desync_frames_bucket_total{bucket="1_2"} 5365
telemt_desync_frames_bucket_total{bucket="3_10"} 8390
telemt_desync_frames_bucket_total{bucket="gt_10"} 8162
telemt_pool_swap_total 106
telemt_pool_force_close_total 3123
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 32690
telemt_me_writer_removed_unexpected_total 734
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2735
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30698
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2908
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29567
telemt_me_writer_teardown_success_total{mode="normal"} 33433
telemt_me_writer_teardown_noop_total 32701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66134
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 23.460968
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66134
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 710
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4512641
telemt_user_connections_current{user="hello"} 1611
telemt_user_octets_from_client{user="hello"} 131697754663 (122.65 GB)
telemt_user_octets_to_client{user="hello"} 2067833212047 (1.88 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 773
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 98829.8 (27h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19991937
telemt_connections_bad_total 1479678
telemt_connections_current 2230
telemt_connections_me_current 2230
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 578228
telemt_upstream_connect_attempt_total 189338
telemt_upstream_connect_success_total 171708
telemt_upstream_connect_fail_total 16036
telemt_upstream_connect_attempts_per_request{bucket="1"} 187744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121477
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40127
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8883
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16036
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64361
telemt_me_reconnect_success_total 2166
telemt_me_reader_eof_total 1352
telemt_me_idle_close_by_peer_total 1351
telemt_me_route_drop_no_conn_total 39451024
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16267820
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 762
telemt_me_single_endpoint_outage_enter_total 123
telemt_me_single_endpoint_outage_exit_total 123
telemt_me_single_endpoint_outage_reconnect_attempt_total 259
telemt_me_single_endpoint_outage_reconnect_success_total 62
telemt_me_single_endpoint_quarantine_bypass_total 259
telemt_me_single_endpoint_shadow_rotate_total 771
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
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
telemt_desync_total 31325
telemt_desync_full_logged_total 9325
telemt_desync_suppressed_total 22000
telemt_desync_frames_bucket_total{bucket="1_2"} 6831
telemt_desync_frames_bucket_total{bucket="3_10"} 13871
telemt_desync_frames_bucket_total{bucket="gt_10"} 10623
telemt_pool_swap_total 101
telemt_pool_force_close_total 3346
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 760
telemt_me_draining_writers_reap_progress_total 30683
telemt_me_writer_removed_unexpected_total 2012
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28215
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2830
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27337
telemt_me_writer_teardown_success_total{mode="normal"} 32430
telemt_me_writer_teardown_noop_total 30709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58974
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 61779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 62703
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63134
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63139
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 211.558083
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63139
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 760
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1499
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 16395750
telemt_user_connections_current{user="hello"} 2230
telemt_user_octets_from_client{user="hello"} 187740587008 (174.85 GB)
telemt_user_octets_to_client{user="hello"} 1119335687546 (1.02 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1012
telemt_user_unique_ips_recent_window{user="hello"} 216
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 98797.4 (27h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5838432
telemt_connections_bad_total 551705
telemt_connections_current 1552
telemt_connections_me_current 1552
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 120600
telemt_upstream_connect_attempt_total 54387
telemt_upstream_connect_success_total 53765
telemt_upstream_connect_fail_total 531
telemt_upstream_connect_attempts_per_request{bucket="1"} 54296
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31963
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21460
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 531
telemt_me_reconnect_attempts_total 68092
telemt_me_reconnect_success_total 1691
telemt_me_reader_eof_total 1467
telemt_me_idle_close_by_peer_total 1466
telemt_me_route_drop_no_conn_total 2357527
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4549008
telemt_me_endpoint_quarantine_total 656
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 740
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
telemt_desync_total 22984
telemt_desync_full_logged_total 8054
telemt_desync_suppressed_total 14930
telemt_desync_frames_bucket_total{bucket="1_2"} 4359
telemt_desync_frames_bucket_total{bucket="3_10"} 8906
telemt_desync_frames_bucket_total{bucket="gt_10"} 9719
telemt_pool_swap_total 101
telemt_pool_force_close_total 2974
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 376
telemt_me_draining_writers_reap_progress_total 34096
telemt_me_writer_removed_unexpected_total 1513
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3623
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32009
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2573
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31122
telemt_me_writer_teardown_success_total{mode="normal"} 35632
telemt_me_writer_teardown_noop_total 34097
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68514
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69306
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69729
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.927672
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69729
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 376
telemt_me_refill_failed_total 4118
telemt_me_writer_restored_same_endpoint_total 1427
telemt_me_writer_restored_fallback_total 29
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 4542115
telemt_user_connections_current{user="hello"} 1552
telemt_user_octets_from_client{user="hello"} 121964426504 (113.59 GB)
telemt_user_octets_to_client{user="hello"} 1856164666290 (1.69 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 754
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 35633.2 (9h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3708070
telemt_connections_bad_total 131446
telemt_connections_current 1212
telemt_connections_me_current 1212
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1541668
telemt_upstream_connect_attempt_total 22636
telemt_upstream_connect_success_total 22492
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 22629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15038
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7388
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 45589
telemt_me_reconnect_success_total 888
telemt_me_reader_eof_total 561
telemt_me_idle_close_by_peer_total 561
telemt_me_route_drop_no_conn_total 996189
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1794159
telemt_me_endpoint_quarantine_total 251
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 269
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 9971
telemt_desync_full_logged_total 3416
telemt_desync_suppressed_total 6555
telemt_desync_frames_bucket_total{bucket="1_2"} 1764
telemt_desync_frames_bucket_total{bucket="3_10"} 3817
telemt_desync_frames_bucket_total{bucket="gt_10"} 4390
telemt_pool_swap_total 38
telemt_pool_force_close_total 1246
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 120
telemt_me_draining_writers_reap_progress_total 12111
telemt_me_writer_removed_unexpected_total 641
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1304
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11468
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1040
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 10865
telemt_me_writer_teardown_success_total{mode="normal"} 12772
telemt_me_writer_teardown_noop_total 12113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 24691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 24779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 24885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 24885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 24885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 24885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 24885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 24885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 24885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 24885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 24885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 24885
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.089015
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 24885
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 120
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 797
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1797902
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 52546681288 (48.94 GB)
telemt_user_octets_to_client{user="hello"} 769981178958 (717.10 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 647
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 16604.0 (4h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160182
telemt_connections_bad_total 1398
telemt_connections_current 313
telemt_connections_me_current 313
telemt_handshake_timeouts_total 3828
telemt_upstream_connect_attempt_total 7633
telemt_upstream_connect_success_total 7613
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 7632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 160
telemt_me_reconnect_success_total 98
telemt_me_reader_eof_total 98
telemt_me_idle_close_by_peer_total 98
telemt_me_route_drop_no_conn_total 45447
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140753
telemt_me_endpoint_quarantine_total 152
telemt_me_single_endpoint_shadow_rotate_total 148
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 973
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 731
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 18
telemt_pool_force_close_total 421
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 6857
telemt_me_writer_removed_unexpected_total 96
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 449
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6506
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6436
telemt_me_writer_teardown_success_total{mode="normal"} 6955
telemt_me_writer_teardown_noop_total 6857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 13669
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13812
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.785241
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13812
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 90
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 140490
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 2586036432 (2.41 GB)
telemt_user_octets_to_client{user="hello"} 81296377528 (75.71 GB)
telemt_user_unique_ips_current{user="hello"} 140
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 98802.1 (27h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7034886
telemt_connections_bad_total 713306
telemt_connections_current 1803
telemt_connections_me_current 1803
telemt_handshake_timeouts_total 200385
telemt_upstream_connect_attempt_total 37817
telemt_upstream_connect_success_total 37670
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 37780
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18908
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 1496
telemt_me_reconnect_success_total 783
telemt_me_reader_eof_total 761
telemt_me_idle_close_by_peer_total 761
telemt_me_route_drop_no_conn_total 2097454
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5313766
telemt_me_endpoint_quarantine_total 676
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 756
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 20533
telemt_desync_full_logged_total 6853
telemt_desync_suppressed_total 13680
telemt_desync_frames_bucket_total{bucket="1_2"} 5008
telemt_desync_frames_bucket_total{bucket="3_10"} 7447
telemt_desync_frames_bucket_total{bucket="gt_10"} 8078
telemt_pool_swap_total 109
telemt_pool_force_close_total 2968
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 370
telemt_me_draining_writers_reap_progress_total 34031
telemt_me_writer_removed_unexpected_total 736
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2747
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32035
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2880
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31063
telemt_me_writer_teardown_success_total{mode="normal"} 34782
telemt_me_writer_teardown_noop_total 34033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68815
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.562866
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68815
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 370
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 698
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5288973
telemt_user_connections_current{user="hello"} 1803
telemt_user_octets_from_client{user="hello"} 107616290908 (100.23 GB)
telemt_user_octets_to_client{user="hello"} 2484878506648 (2.26 TB)
telemt_user_unique_ips_current{user="hello"} 799
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 98798.7 (27h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6026116
telemt_connections_bad_total 591053
telemt_connections_current 1709
telemt_connections_me_current 1709
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 167285
telemt_upstream_connect_attempt_total 53820
telemt_upstream_connect_success_total 53411
telemt_upstream_connect_fail_total 350
telemt_upstream_connect_attempts_per_request{bucket="1"} 53761
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20707
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 350
telemt_me_reconnect_attempts_total 5334
telemt_me_reconnect_success_total 1092
telemt_me_reader_eof_total 970
telemt_me_idle_close_by_peer_total 970
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2150915
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4683591
telemt_me_endpoint_quarantine_total 782
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 751
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
telemt_desync_total 19296
telemt_desync_full_logged_total 6481
telemt_desync_suppressed_total 12815
telemt_desync_frames_bucket_total{bucket="1_2"} 4859
telemt_desync_frames_bucket_total{bucket="3_10"} 7014
telemt_desync_frames_bucket_total{bucket="gt_10"} 7423
telemt_pool_swap_total 107
telemt_pool_force_close_total 2933
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 366
telemt_me_draining_writers_reap_progress_total 32808
telemt_me_writer_removed_unexpected_total 983
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3232
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30603
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2710
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29875
telemt_me_writer_teardown_success_total{mode="normal"} 33835
telemt_me_writer_teardown_noop_total 32812
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66647
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.894022
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66647
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 366
telemt_me_refill_failed_total 245
telemt_me_writer_restored_same_endpoint_total 847
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 4686860
telemt_user_connections_current{user="hello"} 1709
telemt_user_octets_from_client{user="hello"} 88718119593 (82.63 GB)
telemt_user_octets_to_client{user="hello"} 2010922492820 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 768
telemt_user_unique_ips_recent_window{user="hello"} 172
```