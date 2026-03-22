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

# Server Metrics 2026-03-22 17:51:10 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 74687.4 (20h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2703733
telemt_connections_bad_total 154922
telemt_connections_current 1513
telemt_connections_me_current 1513
telemt_handshake_timeouts_total 92518
telemt_upstream_connect_attempt_total 27462
telemt_upstream_connect_success_total 27461
telemt_upstream_connect_attempts_per_request{bucket="1"} 27461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9507
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 64
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1123
telemt_me_reconnect_success_total 475
telemt_me_reader_eof_total 477
telemt_me_idle_close_by_peer_total 477
telemt_me_route_drop_no_conn_total 2218801
telemt_me_route_drop_channel_closed_total 926
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2301139
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 507
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 582
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
telemt_desync_total 10602
telemt_desync_full_logged_total 3354
telemt_desync_suppressed_total 7248
telemt_desync_frames_bucket_total{bucket="1_2"} 2837
telemt_desync_frames_bucket_total{bucket="3_10"} 3943
telemt_desync_frames_bucket_total{bucket="gt_10"} 3822
telemt_pool_swap_total 82
telemt_pool_force_close_total 2542
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 517
telemt_me_draining_writers_reap_progress_total 25068
telemt_me_writer_removed_unexpected_total 463
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1835
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23466
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2490
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 52
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22526
telemt_me_writer_teardown_success_total{mode="normal"} 25301
telemt_me_writer_teardown_noop_total 25078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50379
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50379
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 247.991501
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50379
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 517
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 420
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 2297363
telemt_user_connections_current{user="hello"} 1513
telemt_user_octets_from_client{user="hello"} 33991946268 (31.66 GB)
telemt_user_octets_to_client{user="hello"} 608350212680 (566.57 GB)
telemt_user_unique_ips_current{user="hello"} 586
telemt_user_unique_ips_recent_window{user="hello"} 228
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 88053.4 (24h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3699655
telemt_connections_bad_total 335063
telemt_connections_current 948
telemt_connections_me_current 948
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 94036
telemt_upstream_connect_attempt_total 54223
telemt_upstream_connect_success_total 53550
telemt_upstream_connect_fail_total 593
telemt_upstream_connect_attempts_per_request{bucket="1"} 54143
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22625
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 174
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 593
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 6258
telemt_me_reconnect_success_total 2266
telemt_me_reader_eof_total 2197
telemt_me_idle_close_by_peer_total 2197
telemt_me_route_drop_no_conn_total 3564366
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2935330
telemt_me_endpoint_quarantine_total 694
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 39
telemt_me_single_endpoint_outage_exit_total 39
telemt_me_single_endpoint_outage_reconnect_attempt_total 39
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 39
telemt_me_single_endpoint_shadow_rotate_total 680
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 11563
telemt_desync_full_logged_total 6459
telemt_desync_suppressed_total 5104
telemt_desync_frames_bucket_total{bucket="1_2"} 2681
telemt_desync_frames_bucket_total{bucket="3_10"} 4535
telemt_desync_frames_bucket_total{bucket="gt_10"} 4347
telemt_pool_swap_total 83
telemt_pool_force_close_total 2495
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 211
telemt_me_draining_writers_reap_progress_total 34891
telemt_me_writer_removed_unexpected_total 2148
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4161
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32888
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 362
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32396
telemt_me_writer_teardown_success_total{mode="normal"} 37049
telemt_me_writer_teardown_noop_total 34891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71925
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71940
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.280820
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71940
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 211
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 1956
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 167
telemt_user_connections_total{user="hello"} 2946229
telemt_user_connections_current{user="hello"} 948
telemt_user_octets_from_client{user="hello"} 37861985983 (35.26 GB)
telemt_user_octets_to_client{user="hello"} 673368181446 (627.12 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 575
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 162913.1 (45h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15601027
telemt_connections_bad_total 1490963
telemt_connections_current 2514
telemt_connections_me_current 2514
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 383086
telemt_upstream_connect_attempt_total 73074
telemt_upstream_connect_success_total 72977
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 72994
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34722
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2708
telemt_me_reconnect_success_total 1395
telemt_me_reader_eof_total 1333
telemt_me_idle_close_by_peer_total 1331
telemt_me_route_drop_no_conn_total 13876058
telemt_me_route_drop_channel_closed_total 140
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12437710
telemt_me_endpoint_quarantine_total 1020
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1211
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 50973
telemt_desync_full_logged_total 16004
telemt_desync_suppressed_total 34969
telemt_desync_frames_bucket_total{bucket="1_2"} 11385
telemt_desync_frames_bucket_total{bucket="3_10"} 19896
telemt_desync_frames_bucket_total{bucket="gt_10"} 19692
telemt_pool_swap_total 175
telemt_pool_force_close_total 5937
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 960
telemt_me_draining_writers_reap_progress_total 53504
telemt_me_writer_removed_unexpected_total 1287
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4673
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49409
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5475
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 462
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47567
telemt_me_writer_teardown_success_total{mode="normal"} 54082
telemt_me_writer_teardown_noop_total 53554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106033
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107628
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107636
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 304.654966
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107636
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 960
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 1200
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 12438656
telemt_user_connections_current{user="hello"} 2514
telemt_user_octets_from_client{user="hello"} 179725432301 (167.38 GB)
telemt_user_octets_to_client{user="hello"} 3243987041179 (2.95 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 981
telemt_user_unique_ips_recent_window{user="hello"} 299
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 162914.5 (45h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11251438
telemt_connections_bad_total 1100143
telemt_connections_current 1487
telemt_connections_me_current 1487
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 337277
telemt_upstream_connect_attempt_total 85487
telemt_upstream_connect_success_total 84287
telemt_upstream_connect_fail_total 838
telemt_upstream_connect_attempts_per_request{bucket="1"} 85125
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34631
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3701
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 838
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 187
telemt_me_reconnect_attempts_total 4047
telemt_me_reconnect_success_total 1677
telemt_me_reader_eof_total 1546
telemt_me_idle_close_by_peer_total 1546
telemt_me_route_drop_no_conn_total 4418430
telemt_me_route_drop_channel_closed_total 489
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8385338
telemt_me_endpoint_quarantine_total 1027
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1230
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
telemt_me_writers_active_current 43
telemt_desync_total 37288
telemt_desync_full_logged_total 12547
telemt_desync_suppressed_total 24741
telemt_desync_frames_bucket_total{bucket="1_2"} 9163
telemt_desync_frames_bucket_total{bucket="3_10"} 14358
telemt_desync_frames_bucket_total{bucket="gt_10"} 13767
telemt_pool_swap_total 172
telemt_pool_force_close_total 5364
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 684
telemt_me_draining_writers_reap_progress_total 51906
telemt_me_writer_removed_unexpected_total 1585
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4813
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48522
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4866
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 498
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46542
telemt_me_writer_teardown_success_total{mode="normal"} 53335
telemt_me_writer_teardown_noop_total 51929
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 101862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105264
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 101.948375
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105264
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 684
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 1437
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 133
telemt_user_connections_total{user="hello"} 8323837
telemt_user_connections_current{user="hello"} 1487
telemt_user_octets_from_client{user="hello"} 207888623301 (193.61 GB)
telemt_user_octets_to_client{user="hello"} 3752900251438 (3.41 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 209
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 162878.5 (45h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10604634
telemt_connections_bad_total 914035
telemt_connections_current 1417
telemt_connections_me_current 1417
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 339666
telemt_upstream_connect_attempt_total 70637
telemt_upstream_connect_success_total 69640
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 69822
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1415
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4791
telemt_me_reconnect_success_total 1936
telemt_me_reader_eof_total 1688
telemt_me_idle_close_by_peer_total 1687
telemt_me_route_drop_no_conn_total 5178990
telemt_me_route_drop_channel_closed_total 368
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8004135
telemt_me_endpoint_quarantine_total 1107
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1197
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 36817
telemt_desync_full_logged_total 12179
telemt_desync_suppressed_total 24638
telemt_desync_frames_bucket_total{bucket="1_2"} 9309
telemt_desync_frames_bucket_total{bucket="3_10"} 14084
telemt_desync_frames_bucket_total{bucket="gt_10"} 13424
telemt_pool_swap_total 170
telemt_pool_force_close_total 5290
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 688
telemt_me_draining_writers_reap_progress_total 52232
telemt_me_writer_removed_unexpected_total 1830
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5228
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48747
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4748
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46942
telemt_me_writer_teardown_success_total{mode="normal"} 53975
telemt_me_writer_teardown_noop_total 52303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 100752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106278
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3172.211183
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106278
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 688
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 1675
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 145
telemt_user_connections_total{user="hello"} 7996915
telemt_user_connections_current{user="hello"} 1417
telemt_user_octets_from_client{user="hello"} 184774527537 (172.08 GB)
telemt_user_octets_to_client{user="hello"} 3327885950785 (3.03 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 581
telemt_user_unique_ips_recent_window{user="hello"} 203
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 33158.7 (9h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10435901
telemt_connections_bad_total 639595
telemt_connections_current 2272
telemt_connections_me_current 2272
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 205753
telemt_upstream_connect_attempt_total 41613
telemt_upstream_connect_success_total 39513
telemt_upstream_connect_fail_total 1482
telemt_upstream_connect_attempts_per_request{bucket="1"} 40995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11870
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1389
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5916
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1482
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 6163
telemt_me_reconnect_success_total 791
telemt_me_reader_eof_total 494
telemt_me_idle_close_by_peer_total 494
telemt_me_route_drop_no_conn_total 25053044
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8674346
telemt_me_endpoint_quarantine_total 209
telemt_me_single_endpoint_outage_enter_total 59
telemt_me_single_endpoint_outage_exit_total 59
telemt_me_single_endpoint_outage_reconnect_attempt_total 110
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 110
telemt_me_single_endpoint_shadow_rotate_total 260
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_desync_total 13757
telemt_desync_full_logged_total 3584
telemt_desync_suppressed_total 10173
telemt_desync_frames_bucket_total{bucket="1_2"} 2539
telemt_desync_frames_bucket_total{bucket="3_10"} 5580
telemt_desync_frames_bucket_total{bucket="gt_10"} 5638
telemt_pool_swap_total 32
telemt_pool_force_close_total 1215
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 385
telemt_me_draining_writers_reap_progress_total 9296
telemt_me_writer_removed_unexpected_total 697
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1452
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8503
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 933
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 282
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8081
telemt_me_writer_teardown_success_total{mode="normal"} 9955
telemt_me_writer_teardown_noop_total 9301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 17706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 18187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 18800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19207
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19256
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.172677
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19256
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 385
telemt_me_refill_failed_total 297
telemt_me_writer_restored_same_endpoint_total 530
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 8696047
telemt_user_connections_current{user="hello"} 2272
telemt_user_octets_from_client{user="hello"} 73911486783 (68.84 GB)
telemt_user_octets_to_client{user="hello"} 377106674629 (351.21 GB)
telemt_user_msgs_from_client{user="hello"} 57283
telemt_user_msgs_to_client{user="hello"} 45481
telemt_user_unique_ips_current{user="hello"} 827
telemt_user_unique_ips_recent_window{user="hello"} 313
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 162885.3 (45h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10433243
telemt_connections_bad_total 877927
telemt_connections_current 1842
telemt_connections_me_current 1842
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 231216
telemt_upstream_connect_attempt_total 99350
telemt_upstream_connect_success_total 98321
telemt_upstream_connect_fail_total 874
telemt_upstream_connect_attempts_per_request{bucket="1"} 99195
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 60433
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36333
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1317
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 874
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 72103
telemt_me_reconnect_success_total 2676
telemt_me_reader_eof_total 2378
telemt_me_idle_close_by_peer_total 2376
telemt_me_route_drop_no_conn_total 5117595
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8232073
telemt_me_endpoint_quarantine_total 1089
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 1212
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 43414
telemt_desync_full_logged_total 14815
telemt_desync_suppressed_total 28599
telemt_desync_frames_bucket_total{bucket="1_2"} 8827
telemt_desync_frames_bucket_total{bucket="3_10"} 16720
telemt_desync_frames_bucket_total{bucket="gt_10"} 17867
telemt_pool_swap_total 166
telemt_pool_force_close_total 4935
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 617
telemt_me_draining_writers_reap_progress_total 55344
telemt_me_writer_removed_unexpected_total 2419
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5916
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51870
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4249
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 686
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50409
telemt_me_writer_teardown_success_total{mode="normal"} 57786
telemt_me_writer_teardown_noop_total 55345
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 111112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112815
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 113121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 113124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 113124
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 113127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 113131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 113131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 113131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 113131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 113131
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.601164
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 113131
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 617
telemt_me_refill_failed_total 4279
telemt_me_writer_restored_same_endpoint_total 2244
telemt_me_writer_restored_fallback_total 46
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7365
telemt_me_writer_removed_unexpected_minus_restored_total 129
telemt_user_connections_total{user="hello"} 8235761
telemt_user_connections_current{user="hello"} 1842
telemt_user_octets_from_client{user="hello"} 186961122653 (174.12 GB)
telemt_user_octets_to_client{user="hello"} 3111093485284 (2.83 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 712
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 99721.4 (27h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10907909
telemt_connections_bad_total 417797
telemt_connections_current 1609
telemt_connections_me_current 1609
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4538477
telemt_upstream_connect_attempt_total 47586
telemt_upstream_connect_success_total 47230
telemt_upstream_connect_fail_total 347
telemt_upstream_connect_attempts_per_request{bucket="1"} 47577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20808
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 169
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 347
telemt_me_reconnect_attempts_total 48239
telemt_me_reconnect_success_total 1573
telemt_me_reader_eof_total 1231
telemt_me_idle_close_by_peer_total 1230
telemt_me_route_drop_no_conn_total 3967688
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5242770
telemt_me_endpoint_quarantine_total 644
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 749
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 29230
telemt_desync_full_logged_total 9902
telemt_desync_suppressed_total 19328
telemt_desync_frames_bucket_total{bucket="1_2"} 5892
telemt_desync_frames_bucket_total{bucket="3_10"} 11539
telemt_desync_frames_bucket_total{bucket="gt_10"} 11799
telemt_pool_swap_total 105
telemt_pool_force_close_total 3223
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 335
telemt_me_draining_writers_reap_progress_total 34340
telemt_me_writer_removed_unexpected_total 1291
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3079
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32585
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2801
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 422
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31117
telemt_me_writer_teardown_success_total{mode="normal"} 35664
telemt_me_writer_teardown_noop_total 34347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69512
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69784
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70011
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70011
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.139585
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70011
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 335
telemt_me_refill_failed_total 2712
telemt_me_writer_restored_same_endpoint_total 1397
telemt_me_writer_restored_fallback_total 16
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4330
telemt_user_connections_total{user="hello"} 5235991
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 113147205808 (105.38 GB)
telemt_user_octets_to_client{user="hello"} 1990619154658 (1.81 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 620
telemt_user_unique_ips_recent_window{user="hello"} 225
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 80692.2 (22h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1142371
telemt_connections_bad_total 19258
telemt_connections_current 1184
telemt_connections_me_current 1184
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 21337
telemt_upstream_connect_attempt_total 38985
telemt_upstream_connect_success_total 38871
telemt_upstream_connect_fail_total 89
telemt_upstream_connect_attempts_per_request{bucket="1"} 38960
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17619
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20645
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 607
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 89
telemt_me_reconnect_attempts_total 1752
telemt_me_reconnect_success_total 745
telemt_me_reader_eof_total 721
telemt_me_idle_close_by_peer_total 721
telemt_me_route_drop_no_conn_total 398893
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1016306
telemt_me_endpoint_quarantine_total 683
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 665
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 15
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
telemt_desync_total 5890
telemt_desync_full_logged_total 1797
telemt_desync_suppressed_total 4093
telemt_desync_frames_bucket_total{bucket="1_2"} 1380
telemt_desync_frames_bucket_total{bucket="3_10"} 2311
telemt_desync_frames_bucket_total{bucket="gt_10"} 2199
telemt_pool_swap_total 86
telemt_pool_force_close_total 2208
telemt_me_writer_close_signal_drop_total 126
telemt_me_draining_writers_reap_progress_total 32369
telemt_me_writer_removed_unexpected_total 695
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2503
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30589
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2125
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 83
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30161
telemt_me_writer_teardown_success_total{mode="normal"} 33092
telemt_me_writer_teardown_noop_total 32372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65464
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.842788
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65464
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 126
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 635
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1012687
telemt_user_connections_current{user="hello"} 1184
telemt_user_octets_from_client{user="hello"} 18622381361 (17.34 GB)
telemt_user_octets_to_client{user="hello"} 434921239883 (405.05 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 443
telemt_user_unique_ips_recent_window{user="hello"} 178
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 162889.8 (45h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12715779
telemt_connections_bad_total 1476167
telemt_connections_current 1879
telemt_connections_me_current 1879
telemt_handshake_timeouts_total 357159
telemt_upstream_connect_attempt_total 61292
telemt_upstream_connect_success_total 60997
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 61185
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30842
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_reconnect_attempts_total 2409
telemt_me_reconnect_success_total 1273
telemt_me_reader_eof_total 1236
telemt_me_idle_close_by_peer_total 1236
telemt_me_route_drop_no_conn_total 4284779
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 37
telemt_me_route_drop_queue_full_profile_total{profile="high"} 37
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9619804
telemt_me_endpoint_quarantine_total 1085
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1215
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 39506
telemt_desync_full_logged_total 12891
telemt_desync_suppressed_total 26615
telemt_desync_frames_bucket_total{bucket="1_2"} 9410
telemt_desync_frames_bucket_total{bucket="3_10"} 14612
telemt_desync_frames_bucket_total{bucket="gt_10"} 15484
telemt_pool_swap_total 180
telemt_pool_force_close_total 4965
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 635
telemt_me_draining_writers_reap_progress_total 55149
telemt_me_writer_removed_unexpected_total 1188
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4538
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51833
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4791
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50184
telemt_me_writer_teardown_success_total{mode="normal"} 56371
telemt_me_writer_teardown_noop_total 55151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111389
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111522
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.525852
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111522
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 635
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 1112
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 9587945
telemt_user_connections_current{user="hello"} 1879
telemt_user_octets_from_client{user="hello"} 187825606384 (174.93 GB)
telemt_user_octets_to_client{user="hello"} 4234040002452 (3.85 TB)
telemt_user_unique_ips_current{user="hello"} 655
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 162886.5 (45h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11036353
telemt_connections_bad_total 1236178
telemt_connections_current 1680
telemt_connections_me_current 1680
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 287308
telemt_upstream_connect_attempt_total 87365
telemt_upstream_connect_success_total 86614
telemt_upstream_connect_fail_total 578
telemt_upstream_connect_attempts_per_request{bucket="1"} 87192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 47555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36097
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2052
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 578
telemt_me_reconnect_attempts_total 9162
telemt_me_reconnect_success_total 2182
telemt_me_reader_eof_total 2035
telemt_me_idle_close_by_peer_total 2035
telemt_me_seq_mismatch_total 76
telemt_me_route_drop_no_conn_total 5503797
telemt_me_route_drop_channel_closed_total 351
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8536288
telemt_me_endpoint_quarantine_total 1238
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 42
telemt_me_single_endpoint_outage_exit_total 42
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1216
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_desync_total 38856
telemt_desync_full_logged_total 12547
telemt_desync_suppressed_total 26309
telemt_desync_frames_bucket_total{bucket="1_2"} 9677
telemt_desync_frames_bucket_total{bucket="3_10"} 14475
telemt_desync_frames_bucket_total{bucket="gt_10"} 14704
telemt_pool_swap_total 171
telemt_pool_force_close_total 4793
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 618
telemt_me_draining_writers_reap_progress_total 54789
telemt_me_writer_removed_unexpected_total 2062
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5726
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 51195
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4337
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 49996
telemt_me_writer_teardown_success_total{mode="normal"} 56921
telemt_me_writer_teardown_noop_total 54794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109153
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111715
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.756509
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111715
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 618
telemt_me_refill_failed_total 358
telemt_me_writer_restored_same_endpoint_total 1775
telemt_me_writer_restored_fallback_total 104
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 8542133
telemt_user_connections_current{user="hello"} 1680
telemt_user_octets_from_client{user="hello"} 150006343133 (139.70 GB)
telemt_user_octets_to_client{user="hello"} 3273251328835 (2.98 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 636
telemt_user_unique_ips_recent_window{user="hello"} 241
```