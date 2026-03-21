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

# Server Metrics 2026-03-21 14:01:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 62749.6 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2105432
telemt_connections_bad_total 104186
telemt_connections_current 1857
telemt_connections_me_current 1857
telemt_handshake_timeouts_total 74192
telemt_upstream_connect_attempt_total 24022
telemt_upstream_connect_success_total 23901
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 23979
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1350
telemt_me_reconnect_success_total 567
telemt_me_reader_eof_total 539
telemt_me_idle_close_by_peer_total 539
telemt_me_route_drop_no_conn_total 1610578
telemt_me_route_drop_channel_closed_total 537
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1669704
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 443
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 494
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 6614
telemt_desync_full_logged_total 2282
telemt_desync_suppressed_total 4332
telemt_desync_frames_bucket_total{bucket="1_2"} 1476
telemt_desync_frames_bucket_total{bucket="3_10"} 2506
telemt_desync_frames_bucket_total{bucket="gt_10"} 2632
telemt_pool_swap_total 68
telemt_pool_force_close_total 2060
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 414
telemt_me_draining_writers_reap_progress_total 21503
telemt_me_writer_removed_unexpected_total 521
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1781
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20035
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1983
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19443
telemt_me_writer_teardown_success_total{mode="normal"} 21816
telemt_me_writer_teardown_noop_total 21509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39118
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43325
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 181.970120
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43325
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 414
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 491
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 1668413
telemt_user_connections_current{user="hello"} 1857
telemt_user_octets_from_client{user="hello"} 24818002099 (23.11 GB)
telemt_user_octets_to_client{user="hello"} 429063712239 (399.60 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 662
telemt_user_unique_ips_recent_window{user="hello"} 397
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 2302.8 (0h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 208439
telemt_connections_bad_total 7653
telemt_connections_current 3169
telemt_connections_me_current 3169
telemt_handshake_timeouts_total 6232
telemt_upstream_connect_attempt_total 748
telemt_upstream_connect_success_total 747
telemt_upstream_connect_attempts_per_request{bucket="1"} 747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 406
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_reconnect_attempts_total 97
telemt_me_reconnect_success_total 17
telemt_me_reader_eof_total 16
telemt_me_idle_close_by_peer_total 16
telemt_me_route_drop_no_conn_total 111779
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183944
telemt_me_endpoint_quarantine_total 19
telemt_me_single_endpoint_shadow_rotate_total 22
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 729
telemt_desync_full_logged_total 286
telemt_desync_suppressed_total 443
telemt_desync_frames_bucket_total{bucket="1_2"} 141
telemt_desync_frames_bucket_total{bucket="3_10"} 264
telemt_desync_frames_bucket_total{bucket="gt_10"} 324
telemt_pool_swap_total 2
telemt_pool_force_close_total 52
telemt_me_writer_close_signal_drop_total 10
telemt_me_draining_writers_reap_progress_total 606
telemt_me_writer_removed_unexpected_total 15
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 582
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 50
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 554
telemt_me_writer_teardown_success_total{mode="normal"} 622
telemt_me_writer_teardown_noop_total 606
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1218
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1228
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.173650
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1228
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 10
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 9
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 181177
telemt_user_connections_current{user="hello"} 3169
telemt_user_octets_from_client{user="hello"} 3751923616 (3.49 GB)
telemt_user_octets_to_client{user="hello"} 43409321460 (40.43 GB)
telemt_user_unique_ips_current{user="hello"} 1514
telemt_user_unique_ips_recent_window{user="hello"} 638
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 62747.4 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4177354
telemt_connections_bad_total 398442
telemt_connections_current 4964
telemt_connections_me_current 4964
telemt_handshake_timeouts_total 160295
telemt_upstream_connect_attempt_total 23761
telemt_upstream_connect_success_total 23721
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 23726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10725
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 911
telemt_me_reconnect_success_total 538
telemt_me_reader_eof_total 536
telemt_me_idle_close_by_peer_total 536
telemt_me_route_drop_no_conn_total 2133884
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3381802
telemt_me_endpoint_quarantine_total 397
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 477
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
telemt_desync_total 14186
telemt_desync_full_logged_total 4790
telemt_desync_suppressed_total 9396
telemt_desync_frames_bucket_total{bucket="1_2"} 3000
telemt_desync_frames_bucket_total{bucket="3_10"} 5578
telemt_desync_frames_bucket_total{bucket="gt_10"} 5608
telemt_pool_swap_total 66
telemt_pool_force_close_total 2121
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 326
telemt_me_draining_writers_reap_progress_total 21572
telemt_me_writer_removed_unexpected_total 517
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1867
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20022
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 186
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19451
telemt_me_writer_teardown_success_total{mode="normal"} 21889
telemt_me_writer_teardown_noop_total 21601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43406
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43490
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43490
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 68.877302
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43490
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 326
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 489
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 3377598
telemt_user_connections_current{user="hello"} 4964
telemt_user_octets_from_client{user="hello"} 56095446172 (52.24 GB)
telemt_user_octets_to_client{user="hello"} 1154818217572 (1.05 TB)
telemt_user_unique_ips_current{user="hello"} 1795
telemt_user_unique_ips_recent_window{user="hello"} 833
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 62749.5 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3423659
telemt_connections_bad_total 381576
telemt_connections_current 4008
telemt_connections_me_current 4008
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 127159
telemt_upstream_connect_attempt_total 28087
telemt_upstream_connect_success_total 27811
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 27946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12866
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 480
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1167
telemt_me_reconnect_success_total 551
telemt_me_reader_eof_total 516
telemt_me_idle_close_by_peer_total 516
telemt_me_route_drop_no_conn_total 1067987
telemt_me_route_drop_channel_closed_total 84
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2478879
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 481
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
telemt_me_writers_active_current 43
telemt_desync_total 11333
telemt_desync_full_logged_total 3839
telemt_desync_suppressed_total 7494
telemt_desync_frames_bucket_total{bucket="1_2"} 2840
telemt_desync_frames_bucket_total{bucket="3_10"} 4370
telemt_desync_frames_bucket_total{bucket="gt_10"} 4123
telemt_pool_swap_total 68
telemt_pool_force_close_total 1941
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 175
telemt_me_draining_writers_reap_progress_total 20731
telemt_me_writer_removed_unexpected_total 501
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1751
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19487
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1812
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 129
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18790
telemt_me_writer_teardown_success_total{mode="normal"} 21238
telemt_me_writer_teardown_noop_total 20732
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40487
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41259
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41756
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41970
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.952996
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41970
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 175
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 465
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 2479291
telemt_user_connections_current{user="hello"} 4008
telemt_user_octets_from_client{user="hello"} 46314293393 (43.13 GB)
telemt_user_octets_to_client{user="hello"} 1161229205967 (1.06 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1530
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 62712.6 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3327424
telemt_connections_bad_total 354689
telemt_connections_current 3586
telemt_connections_me_current 3586
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 96589
telemt_upstream_connect_attempt_total 33258
telemt_upstream_connect_success_total 33027
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 33160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14222
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 281
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 846
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1283
telemt_me_reconnect_success_total 624
telemt_me_reader_eof_total 568
telemt_me_idle_close_by_peer_total 568
telemt_me_route_drop_no_conn_total 1020676
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2438233
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 470
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 20
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
telemt_desync_total 11379
telemt_desync_full_logged_total 3774
telemt_desync_suppressed_total 7605
telemt_desync_frames_bucket_total{bucket="1_2"} 2879
telemt_desync_frames_bucket_total{bucket="3_10"} 4286
telemt_desync_frames_bucket_total{bucket="gt_10"} 4214
telemt_pool_swap_total 66
telemt_pool_force_close_total 1876
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 215
telemt_me_draining_writers_reap_progress_total 22062
telemt_me_writer_removed_unexpected_total 541
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1858
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20780
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1707
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 169
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20186
telemt_me_writer_teardown_success_total{mode="normal"} 22638
telemt_me_writer_teardown_noop_total 22067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44290
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44470
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44705
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.346065
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44705
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 215
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 543
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2442905
telemt_user_connections_current{user="hello"} 3586
telemt_user_octets_from_client{user="hello"} 53217781569 (49.56 GB)
telemt_user_octets_to_client{user="hello"} 1155012429916 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1418
telemt_user_unique_ips_recent_window{user="hello"} 558
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 62751.9 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11374483
telemt_connections_bad_total 768677
telemt_connections_current 6470
telemt_connections_me_current 6470
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 355969
telemt_upstream_connect_attempt_total 112506
telemt_upstream_connect_success_total 102832
telemt_upstream_connect_fail_total 8708
telemt_upstream_connect_attempts_per_request{bucket="1"} 111540
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72960
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24187
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 527
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8708
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3654
telemt_me_reconnect_success_total 1298
telemt_me_reader_eof_total 937
telemt_me_idle_close_by_peer_total 936
telemt_me_route_drop_no_conn_total 21086414
telemt_me_route_drop_channel_closed_total 71
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9316375
telemt_me_endpoint_quarantine_total 483
telemt_me_single_endpoint_outage_enter_total 69
telemt_me_single_endpoint_outage_exit_total 69
telemt_me_single_endpoint_outage_reconnect_attempt_total 154
telemt_me_single_endpoint_outage_reconnect_success_total 30
telemt_me_single_endpoint_quarantine_bypass_total 154
telemt_me_single_endpoint_shadow_rotate_total 493
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
telemt_desync_total 17169
telemt_desync_full_logged_total 5460
telemt_desync_suppressed_total 11709
telemt_desync_frames_bucket_total{bucket="1_2"} 3723
telemt_desync_frames_bucket_total{bucket="3_10"} 7519
telemt_desync_frames_bucket_total{bucket="gt_10"} 5927
telemt_pool_swap_total 63
telemt_pool_force_close_total 2026
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 423
telemt_me_draining_writers_reap_progress_total 20380
telemt_me_writer_removed_unexpected_total 1248
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2678
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18778
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1686
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 340
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18354
telemt_me_writer_teardown_success_total{mode="normal"} 21456
telemt_me_writer_teardown_noop_total 20390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40233
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41803
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41827
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41837
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41846
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 161.594669
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41846
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 423
telemt_me_refill_failed_total 85
telemt_me_writer_restored_same_endpoint_total 916
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 9391130
telemt_user_connections_current{user="hello"} 6471
telemt_user_octets_from_client{user="hello"} 69794009879 (65.00 GB)
telemt_user_octets_to_client{user="hello"} 743258412627 (692.21 GB)
telemt_user_msgs_from_client{user="hello"} 228562
telemt_user_msgs_to_client{user="hello"} 540142
telemt_user_unique_ips_current{user="hello"} 2039
telemt_user_unique_ips_recent_window{user="hello"} 1262
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 62719.4 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3342970
telemt_connections_bad_total 378154
telemt_connections_current 4034
telemt_connections_me_current 4034
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 73844
telemt_upstream_connect_attempt_total 26948
telemt_upstream_connect_success_total 26661
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 26916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12759
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13835
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2582
telemt_me_reconnect_success_total 952
telemt_me_reader_eof_total 945
telemt_me_idle_close_by_peer_total 945
telemt_me_route_drop_no_conn_total 1320602
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2560471
telemt_me_endpoint_quarantine_total 396
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 473
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
telemt_desync_total 12083
telemt_desync_full_logged_total 4201
telemt_desync_suppressed_total 7882
telemt_desync_frames_bucket_total{bucket="1_2"} 2328
telemt_desync_frames_bucket_total{bucket="3_10"} 4826
telemt_desync_frames_bucket_total{bucket="gt_10"} 4929
telemt_pool_swap_total 62
telemt_pool_force_close_total 1797
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 173
telemt_me_draining_writers_reap_progress_total 22574
telemt_me_writer_removed_unexpected_total 916
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2214
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21306
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1554
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 243
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20777
telemt_me_writer_teardown_success_total{mode="normal"} 23520
telemt_me_writer_teardown_noop_total 22575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46095
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46095
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.940849
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46095
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 173
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 816
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 2544977
telemt_user_connections_current{user="hello"} 4034
telemt_user_octets_from_client{user="hello"} 54048257180 (50.34 GB)
telemt_user_octets_to_client{user="hello"} 1098671677294 (1023.22 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1519
telemt_user_unique_ips_recent_window{user="hello"} 613
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 62714.1 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5131165
telemt_connections_bad_total 248821
telemt_connections_current 3847
telemt_connections_me_current 3847
telemt_handshake_timeouts_total 2264572
telemt_upstream_connect_attempt_total 24715
telemt_upstream_connect_success_total 24681
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 24684
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 291
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1098
telemt_me_reconnect_success_total 466
telemt_me_reader_eof_total 467
telemt_me_idle_close_by_peer_total 467
telemt_me_route_drop_no_conn_total 1198192
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2316022
telemt_me_endpoint_quarantine_total 466
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 487
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
telemt_desync_total 11031
telemt_desync_full_logged_total 3878
telemt_desync_suppressed_total 7153
telemt_desync_frames_bucket_total{bucket="1_2"} 2042
telemt_desync_frames_bucket_total{bucket="3_10"} 4342
telemt_desync_frames_bucket_total{bucket="gt_10"} 4647
telemt_pool_swap_total 68
telemt_pool_force_close_total 1750
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 152
telemt_me_draining_writers_reap_progress_total 22100
telemt_me_writer_removed_unexpected_total 449
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1543
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21033
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1680
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20350
telemt_me_writer_teardown_success_total{mode="normal"} 22576
telemt_me_writer_teardown_noop_total 22100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44676
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.881124
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44676
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 152
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 404
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2308979
telemt_user_connections_current{user="hello"} 3847
telemt_user_octets_from_client{user="hello"} 50631242644 (47.15 GB)
telemt_user_octets_to_client{user="hello"} 1064381654528 (991.28 GB)
telemt_user_unique_ips_current{user="hello"} 1501
telemt_user_unique_ips_recent_window{user="hello"} 616
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 60705.3 (16h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1101001
telemt_connections_bad_total 135342
telemt_connections_current 777
telemt_connections_me_current 777
telemt_handshake_timeouts_total 389354
telemt_upstream_connect_attempt_total 28462
telemt_upstream_connect_success_total 28459
telemt_upstream_connect_attempts_per_request{bucket="1"} 28459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1218
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 467
telemt_me_idle_close_by_peer_total 467
telemt_me_route_drop_no_conn_total 229724
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 505414
telemt_me_endpoint_quarantine_total 559
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 513
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
telemt_me_writers_active_current 47
telemt_desync_total 3284
telemt_desync_full_logged_total 1218
telemt_desync_suppressed_total 2066
telemt_desync_frames_bucket_total{bucket="1_2"} 587
telemt_desync_frames_bucket_total{bucket="3_10"} 1172
telemt_desync_frames_bucket_total{bucket="gt_10"} 1525
telemt_pool_swap_total 67
telemt_pool_force_close_total 1527
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 107
telemt_me_draining_writers_reap_progress_total 25510
telemt_me_writer_removed_unexpected_total 441
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1876
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24086
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1524
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23983
telemt_me_writer_teardown_success_total{mode="normal"} 25962
telemt_me_writer_teardown_noop_total 25510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51433
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51464
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51472
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.407683
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51472
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 107
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 381
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 505186
telemt_user_connections_current{user="hello"} 777
telemt_user_octets_from_client{user="hello"} 10450609483 (9.73 GB)
telemt_user_octets_to_client{user="hello"} 190645679353 (177.55 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 62723.8 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3644916
telemt_connections_bad_total 338095
telemt_connections_current 4891
telemt_connections_me_current 4891
telemt_handshake_timeouts_total 112812
telemt_upstream_connect_attempt_total 25485
telemt_upstream_connect_success_total 25382
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 25454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12625
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12725
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_reconnect_attempts_total 1031
telemt_me_reconnect_success_total 583
telemt_me_reader_eof_total 543
telemt_me_idle_close_by_peer_total 543
telemt_me_route_drop_no_conn_total 1064018
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2887005
telemt_me_endpoint_quarantine_total 468
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 482
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
telemt_me_writers_active_current 43
telemt_desync_total 11526
telemt_desync_full_logged_total 3795
telemt_desync_suppressed_total 7731
telemt_desync_frames_bucket_total{bucket="1_2"} 2744
telemt_desync_frames_bucket_total{bucket="3_10"} 4287
telemt_desync_frames_bucket_total{bucket="gt_10"} 4495
telemt_pool_swap_total 69
telemt_pool_force_close_total 1790
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 22885
telemt_me_writer_removed_unexpected_total 533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1791
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21626
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1755
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 35
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21095
telemt_me_writer_teardown_success_total{mode="normal"} 23417
telemt_me_writer_teardown_noop_total 22885
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46065
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46302
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.255565
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46302
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 515
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 2879321
telemt_user_connections_current{user="hello"} 4891
telemt_user_octets_from_client{user="hello"} 60701733676 (56.53 GB)
telemt_user_octets_to_client{user="hello"} 1358129723376 (1.24 TB)
telemt_user_unique_ips_current{user="hello"} 1746
telemt_user_unique_ips_recent_window{user="hello"} 756
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 62721.4 (17h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3286428
telemt_connections_bad_total 290735
telemt_connections_current 4336
telemt_connections_me_current 4336
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 95692
telemt_upstream_connect_attempt_total 41661
telemt_upstream_connect_success_total 41391
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 41614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25872
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14414
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 588
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_reconnect_attempts_total 3536
telemt_me_reconnect_success_total 750
telemt_me_reader_eof_total 658
telemt_me_idle_close_by_peer_total 658
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1117482
telemt_me_route_drop_channel_closed_total 83
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2637085
telemt_me_endpoint_quarantine_total 531
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 482
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 10139
telemt_desync_full_logged_total 3470
telemt_desync_suppressed_total 6669
telemt_desync_frames_bucket_total{bucket="1_2"} 2563
telemt_desync_frames_bucket_total{bucket="3_10"} 3748
telemt_desync_frames_bucket_total{bucket="gt_10"} 3828
telemt_pool_swap_total 68
telemt_pool_force_close_total 1736
telemt_me_writer_close_signal_drop_total 186
telemt_me_draining_writers_reap_progress_total 22035
telemt_me_writer_removed_unexpected_total 670
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2098
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20638
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1621
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 115
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20299
telemt_me_writer_teardown_success_total{mode="normal"} 22736
telemt_me_writer_teardown_noop_total 22036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44763
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44772
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.329096
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44772
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 186
telemt_me_refill_failed_total 158
telemt_me_writer_restored_same_endpoint_total 573
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 2646149
telemt_user_connections_current{user="hello"} 4336
telemt_user_octets_from_client{user="hello"} 48097169461 (44.79 GB)
telemt_user_octets_to_client{user="hello"} 1146818317696 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1516
telemt_user_unique_ips_recent_window{user="hello"} 751
```