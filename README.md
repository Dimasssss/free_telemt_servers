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

Можете писать свой ник в коментарии к переводу

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
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
- Оплачен до: 25 марта
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
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
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

# Server Metrics 2026-03-21 08:30:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 42852.9 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1105297
telemt_connections_bad_total 55889
telemt_connections_current 1378
telemt_connections_me_current 1378
telemt_handshake_timeouts_total 48384
telemt_upstream_connect_attempt_total 17030
telemt_upstream_connect_success_total 16954
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 17006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6040
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 665
telemt_me_reconnect_success_total 301
telemt_me_reader_eof_total 304
telemt_me_idle_close_by_peer_total 304
telemt_me_route_drop_no_conn_total 469737
telemt_me_route_drop_channel_closed_total 160
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 813334
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_endpoint_quarantine_total 302
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 349
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 14
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
telemt_desync_total 3487
telemt_desync_full_logged_total 1230
telemt_desync_suppressed_total 2257
telemt_desync_frames_bucket_total{bucket="1_2"} 724
telemt_desync_frames_bucket_total{bucket="3_10"} 1336
telemt_desync_frames_bucket_total{bucket="gt_10"} 1427
telemt_pool_swap_total 47
telemt_pool_force_close_total 1283
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 169
telemt_me_draining_writers_reap_progress_total 15232
telemt_me_writer_removed_unexpected_total 286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1183
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14265
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13949
telemt_me_writer_teardown_success_total{mode="normal"} 15448
telemt_me_writer_teardown_noop_total 15233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28882
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30681
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 63.721355
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30681
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 169
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 264
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 812658
telemt_user_connections_current{user="hello"} 1378
telemt_user_octets_from_client{user="hello"} 11565006091 (10.77 GB)
telemt_user_octets_to_client{user="hello"} 235891412507 (219.69 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 42854.7 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2688791
telemt_connections_bad_total 303569
telemt_connections_current 4276
telemt_connections_me_current 4276
telemt_handshake_timeouts_total 75829
telemt_upstream_connect_attempt_total 15707
telemt_upstream_connect_success_total 15633
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 15683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6487
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9095
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 943
telemt_me_reconnect_success_total 353
telemt_me_reader_eof_total 347
telemt_me_idle_close_by_peer_total 346
telemt_me_route_drop_no_conn_total 719687
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1719196
telemt_me_endpoint_quarantine_total 278
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 337
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
telemt_desync_total 7618
telemt_desync_full_logged_total 2588
telemt_desync_suppressed_total 5030
telemt_desync_frames_bucket_total{bucket="1_2"} 1537
telemt_desync_frames_bucket_total{bucket="3_10"} 2982
telemt_desync_frames_bucket_total{bucket="gt_10"} 3099
telemt_pool_swap_total 46
telemt_pool_force_close_total 1384
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 14057
telemt_me_writer_removed_unexpected_total 325
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1280
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13097
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1306
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12673
telemt_me_writer_teardown_success_total{mode="normal"} 14377
telemt_me_writer_teardown_noop_total 14057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28434
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.745721
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28434
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 282
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1715715
telemt_user_connections_current{user="hello"} 4276
telemt_user_octets_from_client{user="hello"} 24437828968 (22.76 GB)
telemt_user_octets_to_client{user="hello"} 664980478084 (619.31 GB)
telemt_user_unique_ips_current{user="hello"} 1650
telemt_user_unique_ips_recent_window{user="hello"} 573
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 42851.0 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1947569
telemt_connections_bad_total 243350
telemt_connections_current 3961
telemt_connections_me_current 3961
telemt_handshake_timeouts_total 74195
telemt_upstream_connect_attempt_total 17050
telemt_upstream_connect_success_total 17040
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17041
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7736
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9256
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 567
telemt_me_reconnect_success_total 316
telemt_me_reader_eof_total 328
telemt_me_idle_close_by_peer_total 328
telemt_me_route_drop_no_conn_total 618323
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1496197
telemt_me_endpoint_quarantine_total 295
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 339
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
telemt_desync_total 6227
telemt_desync_full_logged_total 2208
telemt_desync_suppressed_total 4019
telemt_desync_frames_bucket_total{bucket="1_2"} 1395
telemt_desync_frames_bucket_total{bucket="3_10"} 2406
telemt_desync_frames_bucket_total{bucket="gt_10"} 2426
telemt_pool_swap_total 46
telemt_pool_force_close_total 1350
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 168
telemt_me_draining_writers_reap_progress_total 15522
telemt_me_writer_removed_unexpected_total 308
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1259
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14474
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1280
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14172
telemt_me_writer_teardown_success_total{mode="normal"} 15733
telemt_me_writer_teardown_noop_total 15531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29508
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31245
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31264
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.466227
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31264
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 168
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 279
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1493550
telemt_user_connections_current{user="hello"} 3961
telemt_user_octets_from_client{user="hello"} 21028327428 (19.58 GB)
telemt_user_octets_to_client{user="hello"} 617872762668 (575.44 GB)
telemt_user_unique_ips_current{user="hello"} 1465
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 42852.3 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1645151
telemt_connections_bad_total 204038
telemt_connections_current 3280
telemt_connections_me_current 3280
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 67820
telemt_upstream_connect_attempt_total 21727
telemt_upstream_connect_success_total 21497
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 21619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11520
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9570
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 820
telemt_me_reconnect_success_total 347
telemt_me_reader_eof_total 323
telemt_me_idle_close_by_peer_total 323
telemt_me_route_drop_no_conn_total 460635
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1124191
telemt_me_endpoint_quarantine_total 307
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 343
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
telemt_me_writers_active_current 45
telemt_desync_total 5289
telemt_desync_full_logged_total 1831
telemt_desync_suppressed_total 3458
telemt_desync_frames_bucket_total{bucket="1_2"} 1288
telemt_desync_frames_bucket_total{bucket="3_10"} 2155
telemt_desync_frames_bucket_total{bucket="gt_10"} 1846
telemt_pool_swap_total 47
telemt_pool_force_close_total 1237
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 15233
telemt_me_writer_removed_unexpected_total 315
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1173
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14389
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13996
telemt_me_writer_teardown_success_total{mode="normal"} 15562
telemt_me_writer_teardown_noop_total 15234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30298
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30733
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30796
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.364252
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30796
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 289
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1126587
telemt_user_connections_current{user="hello"} 3280
telemt_user_octets_from_client{user="hello"} 20533827485 (19.12 GB)
telemt_user_octets_to_client{user="hello"} 543182608367 (505.88 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1222
telemt_user_unique_ips_recent_window{user="hello"} 430
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 42816.2 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1566522
telemt_connections_bad_total 201280
telemt_connections_current 3246
telemt_connections_me_current 3246
telemt_handshake_timeouts_total 50627
telemt_upstream_connect_attempt_total 17922
telemt_upstream_connect_success_total 17910
telemt_upstream_connect_attempts_per_request{bucket="1"} 17910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9900
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 411
telemt_me_reconnect_success_total 312
telemt_me_reader_eof_total 313
telemt_me_idle_close_by_peer_total 313
telemt_me_route_drop_no_conn_total 350755
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1118357
telemt_me_endpoint_quarantine_total 341
telemt_me_single_endpoint_shadow_rotate_total 334
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 11
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
telemt_desync_total 5417
telemt_desync_full_logged_total 1909
telemt_desync_suppressed_total 3508
telemt_desync_frames_bucket_total{bucket="1_2"} 1411
telemt_desync_frames_bucket_total{bucket="3_10"} 2095
telemt_desync_frames_bucket_total{bucket="gt_10"} 1911
telemt_pool_swap_total 46
telemt_pool_force_close_total 1189
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 94
telemt_me_draining_writers_reap_progress_total 16196
telemt_me_writer_removed_unexpected_total 290
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1141
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15370
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15007
telemt_me_writer_teardown_success_total{mode="normal"} 16511
telemt_me_writer_teardown_noop_total 16199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32630
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32710
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.859534
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32710
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 94
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 282
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1116431
telemt_user_connections_current{user="hello"} 3246
telemt_user_octets_from_client{user="hello"} 28344528532 (26.40 GB)
telemt_user_octets_to_client{user="hello"} 578360042636 (538.64 GB)
telemt_user_unique_ips_current{user="hello"} 1209
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 42855.6 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4249028
telemt_connections_bad_total 239155
telemt_connections_current 5048
telemt_connections_me_current 5048
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 197435
telemt_upstream_connect_attempt_total 43453
telemt_upstream_connect_success_total 41485
telemt_upstream_connect_fail_total 1367
telemt_upstream_connect_attempts_per_request{bucket="1"} 42852
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29008
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1266
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1367
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2192
telemt_me_reconnect_success_total 768
telemt_me_reader_eof_total 504
telemt_me_idle_close_by_peer_total 503
telemt_me_route_drop_no_conn_total 6215787
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3533594
telemt_me_endpoint_quarantine_total 346
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 342
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
telemt_me_writers_active_current 48
telemt_desync_total 7618
telemt_desync_full_logged_total 2571
telemt_desync_suppressed_total 5047
telemt_desync_frames_bucket_total{bucket="1_2"} 1694
telemt_desync_frames_bucket_total{bucket="3_10"} 3298
telemt_desync_frames_bucket_total{bucket="gt_10"} 2626
telemt_pool_swap_total 45
telemt_pool_force_close_total 1312
telemt_me_writer_close_signal_drop_total 228
telemt_me_draining_writers_reap_progress_total 14480
telemt_me_writer_removed_unexpected_total 729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1731
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13436
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1194
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13168
telemt_me_writer_teardown_success_total{mode="normal"} 15167
telemt_me_writer_teardown_noop_total 14486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29653
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.621264
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29653
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 228
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 503
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 3555777
telemt_user_connections_current{user="hello"} 5048
telemt_user_octets_from_client{user="hello"} 40862987198 (38.06 GB)
telemt_user_octets_to_client{user="hello"} 523675144854 (487.71 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1767
telemt_user_unique_ips_recent_window{user="hello"} 845
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 42823.3 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1633201
telemt_connections_bad_total 223727
telemt_connections_current 3182
telemt_connections_me_current 3182
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31859
telemt_upstream_connect_attempt_total 19425
telemt_upstream_connect_success_total 19249
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 19408
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9385
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_reconnect_attempts_total 1703
telemt_me_reconnect_success_total 538
telemt_me_reader_eof_total 551
telemt_me_idle_close_by_peer_total 551
telemt_me_route_drop_no_conn_total 429115
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1206407
telemt_me_endpoint_quarantine_total 267
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 341
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
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
telemt_desync_total 5307
telemt_desync_full_logged_total 1968
telemt_desync_suppressed_total 3339
telemt_desync_frames_bucket_total{bucket="1_2"} 1019
telemt_desync_frames_bucket_total{bucket="3_10"} 2165
telemt_desync_frames_bucket_total{bucket="gt_10"} 2123
telemt_pool_swap_total 45
telemt_pool_force_close_total 1153
telemt_me_writer_close_signal_drop_total 73
telemt_me_draining_writers_reap_progress_total 16070
telemt_me_writer_removed_unexpected_total 530
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1394
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15227
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1086
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 67
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14917
telemt_me_writer_teardown_success_total{mode="normal"} 16621
telemt_me_writer_teardown_noop_total 16070
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32691
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.211797
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32691
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 73
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 454
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1203465
telemt_user_connections_current{user="hello"} 3182
telemt_user_octets_from_client{user="hello"} 20935191968 (19.50 GB)
telemt_user_octets_to_client{user="hello"} 567048942586 (528.11 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1280
telemt_user_unique_ips_recent_window{user="hello"} 495
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 42817.8 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2141208
telemt_connections_bad_total 132909
telemt_connections_current 3161
telemt_connections_me_current 3161
telemt_handshake_timeouts_total 807128
telemt_upstream_connect_attempt_total 18278
telemt_upstream_connect_success_total 18244
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 18247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9747
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 274
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 458
telemt_me_reconnect_success_total 277
telemt_me_reader_eof_total 279
telemt_me_idle_close_by_peer_total 279
telemt_me_route_drop_no_conn_total 386034
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1062170
telemt_me_endpoint_quarantine_total 351
telemt_me_single_endpoint_shadow_rotate_total 344
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
telemt_desync_total 5280
telemt_desync_full_logged_total 1866
telemt_desync_suppressed_total 3414
telemt_desync_frames_bucket_total{bucket="1_2"} 902
telemt_desync_frames_bucket_total{bucket="3_10"} 2136
telemt_desync_frames_bucket_total{bucket="gt_10"} 2242
telemt_pool_swap_total 47
telemt_pool_force_close_total 1124
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 16367
telemt_me_writer_removed_unexpected_total 269
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1015
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15640
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1107
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15243
telemt_me_writer_teardown_success_total{mode="normal"} 16655
telemt_me_writer_teardown_noop_total 16367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33022
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33022
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.663663
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33022
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 247
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1058601
telemt_user_connections_current{user="hello"} 3161
telemt_user_octets_from_client{user="hello"} 18394647556 (17.13 GB)
telemt_user_octets_to_client{user="hello"} 537891209116 (500.95 GB)
telemt_user_unique_ips_current{user="hello"} 1240
telemt_user_unique_ips_recent_window{user="hello"} 433
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 40808.8 (11h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 449240
telemt_connections_bad_total 14843
telemt_connections_current 544
telemt_connections_me_current 544
telemt_handshake_timeouts_total 150107
telemt_upstream_connect_attempt_total 20281
telemt_upstream_connect_success_total 20278
telemt_upstream_connect_attempts_per_request{bucket="1"} 20278
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 742
telemt_me_reconnect_success_total 310
telemt_me_reader_eof_total 313
telemt_me_idle_close_by_peer_total 313
telemt_me_route_drop_no_conn_total 99973
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 253416
telemt_me_endpoint_quarantine_total 401
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 353
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
telemt_desync_total 1640
telemt_desync_full_logged_total 680
telemt_desync_suppressed_total 960
telemt_desync_frames_bucket_total{bucket="1_2"} 331
telemt_desync_frames_bucket_total{bucket="3_10"} 679
telemt_desync_frames_bucket_total{bucket="gt_10"} 630
telemt_pool_swap_total 45
telemt_pool_force_close_total 959
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 18125
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1282
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17141
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 957
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17166
telemt_me_writer_teardown_success_total{mode="normal"} 18423
telemt_me_writer_teardown_noop_total 18125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36493
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36548
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.419639
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36548
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 261
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 253600
telemt_user_connections_current{user="hello"} 544
telemt_user_octets_from_client{user="hello"} 3617212143 (3.37 GB)
telemt_user_octets_to_client{user="hello"} 103956423601 (96.82 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 240
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 42827.4 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1671613
telemt_connections_bad_total 143886
telemt_connections_current 3911
telemt_connections_me_current 3911
telemt_handshake_timeouts_total 42725
telemt_upstream_connect_attempt_total 18874
telemt_upstream_connect_success_total 18789
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 18845
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9337
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 662
telemt_me_reconnect_success_total 401
telemt_me_reader_eof_total 368
telemt_me_idle_close_by_peer_total 368
telemt_me_route_drop_no_conn_total 395280
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1312922
telemt_me_endpoint_quarantine_total 345
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 343
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
telemt_me_writers_active_current 48
telemt_desync_total 5266
telemt_desync_full_logged_total 1774
telemt_desync_suppressed_total 3492
telemt_desync_frames_bucket_total{bucket="1_2"} 1282
telemt_desync_frames_bucket_total{bucket="3_10"} 1982
telemt_desync_frames_bucket_total{bucket="gt_10"} 2002
telemt_pool_swap_total 47
telemt_pool_force_close_total 1140
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 96
telemt_me_draining_writers_reap_progress_total 17028
telemt_me_writer_removed_unexpected_total 367
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1243
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16161
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1120
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15888
telemt_me_writer_teardown_success_total{mode="normal"} 17404
telemt_me_writer_teardown_noop_total 17028
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34432
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.122112
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34432
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 96
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 359
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 1307809
telemt_user_connections_current{user="hello"} 3911
telemt_user_octets_from_client{user="hello"} 29054446012 (27.06 GB)
telemt_user_octets_to_client{user="hello"} 605907639696 (564.30 GB)
telemt_user_unique_ips_current{user="hello"} 1487
telemt_user_unique_ips_recent_window{user="hello"} 511
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 42824.2 (11h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1604141
telemt_connections_bad_total 136874
telemt_connections_current 3305
telemt_connections_me_current 3305
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 39803
telemt_upstream_connect_attempt_total 27326
telemt_upstream_connect_success_total 27131
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 27285
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17359
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2781
telemt_me_reconnect_success_total 537
telemt_me_reader_eof_total 456
telemt_me_idle_close_by_peer_total 456
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 402097
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1270902
telemt_me_endpoint_quarantine_total 405
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 339
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
telemt_me_writers_active_current 45
telemt_desync_total 4984
telemt_desync_full_logged_total 1622
telemt_desync_suppressed_total 3362
telemt_desync_frames_bucket_total{bucket="1_2"} 1383
telemt_desync_frames_bucket_total{bucket="3_10"} 1813
telemt_desync_frames_bucket_total{bucket="gt_10"} 1788
telemt_pool_swap_total 47
telemt_pool_force_close_total 1117
telemt_me_writer_close_signal_drop_total 92
telemt_me_draining_writers_reap_progress_total 16140
telemt_me_writer_removed_unexpected_total 465
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1445
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15185
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1069
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15023
telemt_me_writer_teardown_success_total{mode="normal"} 16630
telemt_me_writer_teardown_noop_total 16140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32770
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32770
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.449646
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32770
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 92
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 405
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 32
telemt_user_connections_total{user="hello"} 1275027
telemt_user_connections_current{user="hello"} 3305
telemt_user_octets_from_client{user="hello"} 19521047087 (18.18 GB)
telemt_user_octets_to_client{user="hello"} 565479112219 (526.64 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1238
telemt_user_unique_ips_recent_window{user="hello"} 470
```