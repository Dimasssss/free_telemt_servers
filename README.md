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

# Server Metrics 2026-03-21 08:35:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 43157.9 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1116238
telemt_connections_bad_total 56153
telemt_connections_current 1621
telemt_connections_me_current 1621
telemt_handshake_timeouts_total 48827
telemt_upstream_connect_attempt_total 17111
telemt_upstream_connect_success_total 17035
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 17087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6066
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10921
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 669
telemt_me_reconnect_success_total 304
telemt_me_reader_eof_total 308
telemt_me_idle_close_by_peer_total 308
telemt_me_route_drop_no_conn_total 473558
telemt_me_route_drop_channel_closed_total 162
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 822883
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_endpoint_quarantine_total 302
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 350
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
telemt_desync_total 3555
telemt_desync_full_logged_total 1251
telemt_desync_suppressed_total 2304
telemt_desync_frames_bucket_total{bucket="1_2"} 747
telemt_desync_frames_bucket_total{bucket="3_10"} 1356
telemt_desync_frames_bucket_total{bucket="gt_10"} 1452
telemt_pool_swap_total 47
telemt_pool_force_close_total 1283
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 169
telemt_me_draining_writers_reap_progress_total 15293
telemt_me_writer_removed_unexpected_total 289
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1190
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14323
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1263
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14010
telemt_me_writer_teardown_success_total{mode="normal"} 15513
telemt_me_writer_teardown_noop_total 15294
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30807
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 63.752873
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30807
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 169
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 267
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 19
telemt_user_connections_total{user="hello"} 822185
telemt_user_connections_current{user="hello"} 1621
telemt_user_octets_from_client{user="hello"} 11742881147 (10.94 GB)
telemt_user_octets_to_client{user="hello"} 238218954467 (221.86 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 564
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 43160.4 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2723230
telemt_connections_bad_total 306547
telemt_connections_current 4765
telemt_connections_me_current 4765
telemt_handshake_timeouts_total 76799
telemt_upstream_connect_attempt_total 15761
telemt_upstream_connect_success_total 15687
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 15737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6509
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9127
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_reconnect_attempts_total 943
telemt_me_reconnect_success_total 353
telemt_me_reader_eof_total 347
telemt_me_idle_close_by_peer_total 346
telemt_me_route_drop_no_conn_total 734257
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1747735
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
telemt_desync_total 7757
telemt_desync_full_logged_total 2632
telemt_desync_suppressed_total 5125
telemt_desync_frames_bucket_total{bucket="1_2"} 1580
telemt_desync_frames_bucket_total{bucket="3_10"} 3024
telemt_desync_frames_bucket_total{bucket="gt_10"} 3153
telemt_pool_swap_total 46
telemt_pool_force_close_total 1384
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 14108
telemt_me_writer_removed_unexpected_total 325
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1281
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13147
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1306
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12724
telemt_me_writer_teardown_success_total{mode="normal"} 14428
telemt_me_writer_teardown_noop_total 14108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27370
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28429
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28536
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.752069
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28536
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 282
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 1744261
telemt_user_connections_current{user="hello"} 4765
telemt_user_octets_from_client{user="hello"} 24940079448 (23.23 GB)
telemt_user_octets_to_client{user="hello"} 674356635732 (628.04 GB)
telemt_user_unique_ips_current{user="hello"} 1747
telemt_user_unique_ips_recent_window{user="hello"} 691
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 43156.5 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1978193
telemt_connections_bad_total 248873
telemt_connections_current 4143
telemt_connections_me_current 4143
telemt_handshake_timeouts_total 74470
telemt_upstream_connect_attempt_total 17120
telemt_upstream_connect_success_total 17110
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17111
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7756
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 570
telemt_me_reconnect_success_total 319
telemt_me_reader_eof_total 331
telemt_me_idle_close_by_peer_total 331
telemt_me_route_drop_no_conn_total 627446
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1518963
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
telemt_me_writers_active_current 45
telemt_desync_total 6321
telemt_desync_full_logged_total 2241
telemt_desync_suppressed_total 4080
telemt_desync_frames_bucket_total{bucket="1_2"} 1412
telemt_desync_frames_bucket_total{bucket="3_10"} 2447
telemt_desync_frames_bucket_total{bucket="gt_10"} 2462
telemt_pool_swap_total 46
telemt_pool_force_close_total 1350
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 168
telemt_me_draining_writers_reap_progress_total 15572
telemt_me_writer_removed_unexpected_total 311
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1265
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14521
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1280
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14222
telemt_me_writer_teardown_success_total{mode="normal"} 15786
telemt_me_writer_teardown_noop_total 15581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29610
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31071
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31266
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31367
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.472243
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31367
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 168
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 282
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 24
telemt_user_connections_total{user="hello"} 1516311
telemt_user_connections_current{user="hello"} 4143
telemt_user_octets_from_client{user="hello"} 21343782140 (19.88 GB)
telemt_user_octets_to_client{user="hello"} 627419915520 (584.33 GB)
telemt_user_unique_ips_current{user="hello"} 1566
telemt_user_unique_ips_recent_window{user="hello"} 562
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 43158.4 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1665424
telemt_connections_bad_total 205220
telemt_connections_current 3395
telemt_connections_me_current 3395
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 68059
telemt_upstream_connect_attempt_total 21800
telemt_upstream_connect_success_total 21570
telemt_upstream_connect_fail_total 122
telemt_upstream_connect_attempts_per_request{bucket="1"} 21692
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11547
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9616
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 380
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 122
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 823
telemt_me_reconnect_success_total 349
telemt_me_reader_eof_total 325
telemt_me_idle_close_by_peer_total 325
telemt_me_route_drop_no_conn_total 467683
telemt_me_route_drop_channel_closed_total 33
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1141899
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
telemt_desync_total 5390
telemt_desync_full_logged_total 1859
telemt_desync_suppressed_total 3531
telemt_desync_frames_bucket_total{bucket="1_2"} 1317
telemt_desync_frames_bucket_total{bucket="3_10"} 2190
telemt_desync_frames_bucket_total{bucket="gt_10"} 1883
telemt_pool_swap_total 47
telemt_pool_force_close_total 1237
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 76
telemt_me_draining_writers_reap_progress_total 15284
telemt_me_writer_removed_unexpected_total 317
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1176
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14439
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14047
telemt_me_writer_teardown_success_total{mode="normal"} 15615
telemt_me_writer_teardown_noop_total 15285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 30837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 30880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 30898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 30900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 30900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 30900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 30900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 30900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 30900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 30900
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.368863
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 30900
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 76
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 291
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1144294
telemt_user_connections_current{user="hello"} 3395
telemt_user_octets_from_client{user="hello"} 20775027041 (19.35 GB)
telemt_user_octets_to_client{user="hello"} 552645881043 (514.69 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1284
telemt_user_unique_ips_recent_window{user="hello"} 464
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 43121.8 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1594412
telemt_connections_bad_total 203463
telemt_connections_current 3261
telemt_connections_me_current 3261
telemt_handshake_timeouts_total 50951
telemt_upstream_connect_attempt_total 17996
telemt_upstream_connect_success_total 17984
telemt_upstream_connect_attempts_per_request{bucket="1"} 17984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8021
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 413
telemt_me_reconnect_success_total 314
telemt_me_reader_eof_total 315
telemt_me_idle_close_by_peer_total 315
telemt_me_route_drop_no_conn_total 358579
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1137884
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
telemt_desync_total 5496
telemt_desync_full_logged_total 1941
telemt_desync_suppressed_total 3555
telemt_desync_frames_bucket_total{bucket="1_2"} 1428
telemt_desync_frames_bucket_total{bucket="3_10"} 2125
telemt_desync_frames_bucket_total{bucket="gt_10"} 1943
telemt_pool_swap_total 46
telemt_pool_force_close_total 1189
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 94
telemt_me_draining_writers_reap_progress_total 16252
telemt_me_writer_removed_unexpected_total 292
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1144
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15425
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1151
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 38
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15063
telemt_me_writer_teardown_success_total{mode="normal"} 16569
telemt_me_writer_teardown_noop_total 16255
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32683
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32824
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.861100
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32824
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 94
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 284
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 1135962
telemt_user_connections_current{user="hello"} 3261
telemt_user_octets_from_client{user="hello"} 28544770648 (26.58 GB)
telemt_user_octets_to_client{user="hello"} 585743596548 (545.52 GB)
telemt_user_unique_ips_current{user="hello"} 1251
telemt_user_unique_ips_recent_window{user="hello"} 461
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 43160.3 (11h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4378388
telemt_connections_bad_total 246190
telemt_connections_current 5252
telemt_connections_me_current 5252
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 199672
telemt_upstream_connect_attempt_total 43536
telemt_upstream_connect_success_total 41565
telemt_upstream_connect_fail_total 1367
telemt_upstream_connect_attempts_per_request{bucket="1"} 42932
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29043
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11255
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1267
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1367
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2192
telemt_me_reconnect_success_total 768
telemt_me_reader_eof_total 504
telemt_me_idle_close_by_peer_total 503
telemt_me_route_drop_no_conn_total 6457133
telemt_me_route_drop_channel_closed_total 29
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3648142
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
telemt_desync_total 7758
telemt_desync_full_logged_total 2611
telemt_desync_suppressed_total 5147
telemt_desync_frames_bucket_total{bucket="1_2"} 1729
telemt_desync_frames_bucket_total{bucket="3_10"} 3348
telemt_desync_frames_bucket_total{bucket="gt_10"} 2681
telemt_pool_swap_total 45
telemt_pool_force_close_total 1312
telemt_me_writer_close_signal_drop_total 229
telemt_me_draining_writers_reap_progress_total 14556
telemt_me_writer_removed_unexpected_total 729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1732
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13511
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1194
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 118
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13244
telemt_me_writer_teardown_success_total{mode="normal"} 15243
telemt_me_writer_teardown_noop_total 14562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29805
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.649651
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29805
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 229
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 503
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 218
telemt_user_connections_total{user="hello"} 3670324
telemt_user_connections_current{user="hello"} 5252
telemt_user_octets_from_client{user="hello"} 41188148486 (38.36 GB)
telemt_user_octets_to_client{user="hello"} 526435929290 (490.28 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1852
telemt_user_unique_ips_recent_window{user="hello"} 1375
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 43127.8 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1655195
telemt_connections_bad_total 225193
telemt_connections_current 3287
telemt_connections_me_current 3287
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 32326
telemt_upstream_connect_attempt_total 19495
telemt_upstream_connect_success_total 19318
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 19477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9418
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 42
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_reconnect_attempts_total 1704
telemt_me_reconnect_success_total 539
telemt_me_reader_eof_total 552
telemt_me_idle_close_by_peer_total 552
telemt_me_route_drop_no_conn_total 437598
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1225657
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
telemt_desync_total 5434
telemt_desync_full_logged_total 2009
telemt_desync_suppressed_total 3425
telemt_desync_frames_bucket_total{bucket="1_2"} 1033
telemt_desync_frames_bucket_total{bucket="3_10"} 2212
telemt_desync_frames_bucket_total{bucket="gt_10"} 2189
telemt_pool_swap_total 45
telemt_pool_force_close_total 1153
telemt_me_writer_close_signal_drop_total 73
telemt_me_draining_writers_reap_progress_total 16122
telemt_me_writer_removed_unexpected_total 531
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1399
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15275
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1086
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 67
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14969
telemt_me_writer_teardown_success_total{mode="normal"} 16674
telemt_me_writer_teardown_noop_total 16122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32796
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.212635
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32796
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 73
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 455
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 70
telemt_user_connections_total{user="hello"} 1222715
telemt_user_connections_current{user="hello"} 3287
telemt_user_octets_from_client{user="hello"} 21358509664 (19.89 GB)
telemt_user_octets_to_client{user="hello"} 574827839774 (535.35 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1317
telemt_user_unique_ips_recent_window{user="hello"} 491
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 43122.1 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2176289
telemt_connections_bad_total 134560
telemt_connections_current 3221
telemt_connections_me_current 3221
telemt_handshake_timeouts_total 819131
telemt_upstream_connect_attempt_total 18347
telemt_upstream_connect_success_total 18313
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 18316
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9789
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 275
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 458
telemt_me_reconnect_success_total 277
telemt_me_reader_eof_total 279
telemt_me_idle_close_by_peer_total 279
telemt_me_route_drop_no_conn_total 393740
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1078777
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
telemt_desync_total 5391
telemt_desync_full_logged_total 1904
telemt_desync_suppressed_total 3487
telemt_desync_frames_bucket_total{bucket="1_2"} 933
telemt_desync_frames_bucket_total{bucket="3_10"} 2178
telemt_desync_frames_bucket_total{bucket="gt_10"} 2280
telemt_pool_swap_total 47
telemt_pool_force_close_total 1124
telemt_me_writer_close_signal_drop_total 81
telemt_me_draining_writers_reap_progress_total 16426
telemt_me_writer_removed_unexpected_total 269
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1015
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15699
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1107
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15302
telemt_me_writer_teardown_success_total{mode="normal"} 16714
telemt_me_writer_teardown_noop_total 16426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 33140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 33140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 33140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 33140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 33140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 33140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 33140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 33140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 33140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 33140
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.664100
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 33140
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 81
telemt_me_refill_failed_total 9
telemt_me_writer_restored_same_endpoint_total 247
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 1075210
telemt_user_connections_current{user="hello"} 3221
telemt_user_octets_from_client{user="hello"} 18792431248 (17.50 GB)
telemt_user_octets_to_client{user="hello"} 545748571780 (508.27 GB)
telemt_user_unique_ips_current{user="hello"} 1288
telemt_user_unique_ips_recent_window{user="hello"} 457
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 41113.4 (11h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 455860
telemt_connections_bad_total 14968
telemt_connections_current 571
telemt_connections_me_current 571
telemt_handshake_timeouts_total 151732
telemt_upstream_connect_attempt_total 20382
telemt_upstream_connect_success_total 20380
telemt_upstream_connect_attempts_per_request{bucket="1"} 20380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8510
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11825
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 742
telemt_me_reconnect_success_total 310
telemt_me_reader_eof_total 313
telemt_me_idle_close_by_peer_total 313
telemt_me_route_drop_no_conn_total 101773
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 256766
telemt_me_endpoint_quarantine_total 401
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 354
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
telemt_desync_total 1665
telemt_desync_full_logged_total 687
telemt_desync_suppressed_total 978
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 689
telemt_desync_frames_bucket_total{bucket="gt_10"} 640
telemt_pool_swap_total 45
telemt_pool_force_close_total 959
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 56
telemt_me_draining_writers_reap_progress_total 18227
telemt_me_writer_removed_unexpected_total 295
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1286
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17239
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 957
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17268
telemt_me_writer_teardown_success_total{mode="normal"} 18525
telemt_me_writer_teardown_noop_total 18227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36752
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.422070
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36752
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 56
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 261
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 256949
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 3655274879 (3.40 GB)
telemt_user_octets_to_client{user="hello"} 104647911557 (97.46 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 104
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 43132.3 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1693789
telemt_connections_bad_total 144851
telemt_connections_current 3883
telemt_connections_me_current 3883
telemt_handshake_timeouts_total 43314
telemt_upstream_connect_attempt_total 18956
telemt_upstream_connect_success_total 18871
telemt_upstream_connect_fail_total 56
telemt_upstream_connect_attempts_per_request{bucket="1"} 18927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9467
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9380
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 56
telemt_me_reconnect_attempts_total 666
telemt_me_reconnect_success_total 405
telemt_me_reader_eof_total 372
telemt_me_idle_close_by_peer_total 372
telemt_me_route_drop_no_conn_total 402967
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1332529
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
telemt_me_writers_active_current 50
telemt_desync_total 5361
telemt_desync_full_logged_total 1800
telemt_desync_suppressed_total 3561
telemt_desync_frames_bucket_total{bucket="1_2"} 1312
telemt_desync_frames_bucket_total{bucket="3_10"} 2012
telemt_desync_frames_bucket_total{bucket="gt_10"} 2037
telemt_pool_swap_total 47
telemt_pool_force_close_total 1140
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 96
telemt_me_draining_writers_reap_progress_total 17087
telemt_me_writer_removed_unexpected_total 371
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1247
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16220
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1120
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 20
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15947
telemt_me_writer_teardown_success_total{mode="normal"} 17467
telemt_me_writer_teardown_noop_total 17087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34554
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.124588
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34554
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 96
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 363
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 1327416
telemt_user_connections_current{user="hello"} 3883
telemt_user_octets_from_client{user="hello"} 29331967904 (27.32 GB)
telemt_user_octets_to_client{user="hello"} 617176449644 (574.79 GB)
telemt_user_unique_ips_current{user="hello"} 1500
telemt_user_unique_ips_recent_window{user="hello"} 527
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 43129.2 (11h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1625756
telemt_connections_bad_total 137645
telemt_connections_current 3227
telemt_connections_me_current 3227
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 40384
telemt_upstream_connect_attempt_total 27405
telemt_upstream_connect_success_total 27210
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 27364
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17394
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9786
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_reconnect_attempts_total 2784
telemt_me_reconnect_success_total 539
telemt_me_reader_eof_total 459
telemt_me_idle_close_by_peer_total 459
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 410395
telemt_me_route_drop_channel_closed_total 22
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1289653
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
telemt_desync_total 5067
telemt_desync_full_logged_total 1649
telemt_desync_suppressed_total 3418
telemt_desync_frames_bucket_total{bucket="1_2"} 1409
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 1813
telemt_pool_swap_total 47
telemt_pool_force_close_total 1117
telemt_me_writer_close_signal_drop_total 92
telemt_me_draining_writers_reap_progress_total 16199
telemt_me_writer_removed_unexpected_total 468
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1449
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15243
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1069
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15082
telemt_me_writer_teardown_success_total{mode="normal"} 16692
telemt_me_writer_teardown_noop_total 16199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32891
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.452243
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32891
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 92
telemt_me_refill_failed_total 127
telemt_me_writer_restored_same_endpoint_total 407
telemt_me_writer_restored_fallback_total 28
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 1293782
telemt_user_connections_current{user="hello"} 3227
telemt_user_octets_from_client{user="hello"} 19847401559 (18.48 GB)
telemt_user_octets_to_client{user="hello"} 575329963523 (535.82 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1252
telemt_user_unique_ips_recent_window{user="hello"} 458
```