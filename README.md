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

# Server Metrics 2026-03-21 09:15:55 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 45602.8 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1260403
telemt_connections_bad_total 62261
telemt_connections_current 1485
telemt_connections_me_current 1485
telemt_handshake_timeouts_total 52205
telemt_upstream_connect_attempt_total 17937
telemt_upstream_connect_success_total 17856
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6409
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11398
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 12
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 757
telemt_me_reconnect_success_total 315
telemt_me_reader_eof_total 321
telemt_me_idle_close_by_peer_total 321
telemt_me_route_drop_no_conn_total 704279
telemt_me_route_drop_channel_closed_total 194
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 950496
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 367
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 4047
telemt_desync_full_logged_total 1385
telemt_desync_suppressed_total 2662
telemt_desync_frames_bucket_total{bucket="1_2"} 852
telemt_desync_frames_bucket_total{bucket="3_10"} 1577
telemt_desync_frames_bucket_total{bucket="gt_10"} 1618
telemt_pool_swap_total 50
telemt_pool_force_close_total 1399
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 194
telemt_me_draining_writers_reap_progress_total 16086
telemt_me_writer_removed_unexpected_total 301
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1248
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15042
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14687
telemt_me_writer_teardown_success_total{mode="normal"} 16290
telemt_me_writer_teardown_noop_total 16087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32372
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32377
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 75.966568
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32377
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 194
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 275
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 949731
telemt_user_connections_current{user="hello"} 1485
telemt_user_octets_from_client{user="hello"} 13505710891 (12.58 GB)
telemt_user_octets_to_client{user="hello"} 261614019303 (243.65 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 217
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 45604.0 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3099490
telemt_connections_bad_total 337186
telemt_connections_current 4605
telemt_connections_me_current 4605
telemt_handshake_timeouts_total 89811
telemt_upstream_connect_attempt_total 16501
telemt_upstream_connect_success_total 16425
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 16477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6805
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9566
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_reconnect_attempts_total 979
telemt_me_reconnect_success_total 373
telemt_me_reader_eof_total 367
telemt_me_idle_close_by_peer_total 366
telemt_me_route_drop_no_conn_total 1177764
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2047656
telemt_me_endpoint_quarantine_total 294
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 354
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
telemt_desync_total 8926
telemt_desync_full_logged_total 3001
telemt_desync_suppressed_total 5925
telemt_desync_frames_bucket_total{bucket="1_2"} 1837
telemt_desync_frames_bucket_total{bucket="3_10"} 3494
telemt_desync_frames_bucket_total{bucket="gt_10"} 3595
telemt_pool_swap_total 49
telemt_pool_force_close_total 1478
telemt_me_writer_close_signal_drop_total 174
telemt_me_draining_writers_reap_progress_total 14755
telemt_me_writer_removed_unexpected_total 344
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1361
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13734
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1394
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 84
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13277
telemt_me_writer_teardown_success_total{mode="normal"} 15095
telemt_me_writer_teardown_noop_total 14755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 29087
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 29369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29850
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29850
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.194323
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29850
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 174
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 299
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2043564
telemt_user_connections_current{user="hello"} 4605
telemt_user_octets_from_client{user="hello"} 29317887624 (27.30 GB)
telemt_user_octets_to_client{user="hello"} 736908630408 (686.30 GB)
telemt_user_unique_ips_current{user="hello"} 1696
telemt_user_unique_ips_recent_window{user="hello"} 638
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 45600.4 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2238054
telemt_connections_bad_total 273401
telemt_connections_current 3948
telemt_connections_me_current 3948
telemt_handshake_timeouts_total 83158
telemt_upstream_connect_attempt_total 17919
telemt_upstream_connect_success_total 17909
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8114
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9744
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 604
telemt_me_reconnect_success_total 337
telemt_me_reader_eof_total 350
telemt_me_idle_close_by_peer_total 350
telemt_me_route_drop_no_conn_total 767125
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1735354
telemt_me_endpoint_quarantine_total 305
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 357
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
telemt_me_writers_active_current 45
telemt_desync_total 7403
telemt_desync_full_logged_total 2594
telemt_desync_suppressed_total 4809
telemt_desync_frames_bucket_total{bucket="1_2"} 1606
telemt_desync_frames_bucket_total{bucket="3_10"} 2867
telemt_desync_frames_bucket_total{bucket="gt_10"} 2930
telemt_pool_swap_total 49
telemt_pool_force_close_total 1446
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 183
telemt_me_draining_writers_reap_progress_total 16307
telemt_me_writer_removed_unexpected_total 330
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1333
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15201
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1370
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 76
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14861
telemt_me_writer_teardown_success_total{mode="normal"} 16534
telemt_me_writer_teardown_noop_total 16317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31613
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31979
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32825
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32851
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 32.456506
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32851
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 183
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 300
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 1732440
telemt_user_connections_current{user="hello"} 3948
telemt_user_octets_from_client{user="hello"} 26220296284 (24.42 GB)
telemt_user_octets_to_client{user="hello"} 693276795684 (645.66 GB)
telemt_user_unique_ips_current{user="hello"} 1483
telemt_user_unique_ips_recent_window{user="hello"} 575
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 45601.6 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1881503
telemt_connections_bad_total 226032
telemt_connections_current 3474
telemt_connections_me_current 3474
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 79890
telemt_upstream_connect_attempt_total 22826
telemt_upstream_connect_success_total 22593
telemt_upstream_connect_fail_total 124
telemt_upstream_connect_attempts_per_request{bucket="1"} 22717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10143
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 381
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 124
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 926
telemt_me_reconnect_success_total 426
telemt_me_reader_eof_total 392
telemt_me_idle_close_by_peer_total 392
telemt_me_route_drop_no_conn_total 533461
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1299488
telemt_me_endpoint_quarantine_total 323
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 360
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
telemt_me_writers_active_current 43
telemt_desync_total 6136
telemt_desync_full_logged_total 2098
telemt_desync_suppressed_total 4038
telemt_desync_frames_bucket_total{bucket="1_2"} 1520
telemt_desync_frames_bucket_total{bucket="3_10"} 2444
telemt_desync_frames_bucket_total{bucket="gt_10"} 2172
telemt_pool_swap_total 49
telemt_pool_force_close_total 1331
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 16182
telemt_me_writer_removed_unexpected_total 385
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1291
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15290
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1252
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 79
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14851
telemt_me_writer_teardown_success_total{mode="normal"} 16581
telemt_me_writer_teardown_noop_total 16183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 32183
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 32635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32701
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32764
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.753983
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32764
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 358
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1301639
telemt_user_connections_current{user="hello"} 3474
telemt_user_octets_from_client{user="hello"} 26573022649 (24.75 GB)
telemt_user_octets_to_client{user="hello"} 627521466087 (584.42 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1294
telemt_user_unique_ips_recent_window{user="hello"} 463
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 45565.6 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1799159
telemt_connections_bad_total 213229
telemt_connections_current 3384
telemt_connections_me_current 3384
telemt_handshake_timeouts_total 55665
telemt_upstream_connect_attempt_total 18815
telemt_upstream_connect_success_total 18796
telemt_upstream_connect_attempts_per_request{bucket="1"} 18796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 474
telemt_me_reconnect_success_total 362
telemt_me_reader_eof_total 347
telemt_me_idle_close_by_peer_total 347
telemt_me_route_drop_no_conn_total 495576
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1299891
telemt_me_endpoint_quarantine_total 355
telemt_me_single_endpoint_shadow_rotate_total 352
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
telemt_me_writers_active_current 43
telemt_desync_total 6067
telemt_desync_full_logged_total 2127
telemt_desync_suppressed_total 3940
telemt_desync_frames_bucket_total{bucket="1_2"} 1588
telemt_desync_frames_bucket_total{bucket="3_10"} 2342
telemt_desync_frames_bucket_total{bucket="gt_10"} 2137
telemt_pool_swap_total 49
telemt_pool_force_close_total 1292
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 110
telemt_me_draining_writers_reap_progress_total 16977
telemt_me_writer_removed_unexpected_total 321
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1231
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16096
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1236
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15685
telemt_me_writer_teardown_success_total{mode="normal"} 17327
telemt_me_writer_teardown_noop_total 16980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34111
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34288
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34307
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34307
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.701165
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34307
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 110
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 318
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 1297609
telemt_user_connections_current{user="hello"} 3384
telemt_user_octets_from_client{user="hello"} 31264469184 (29.12 GB)
telemt_user_octets_to_client{user="hello"} 651344763552 (606.61 GB)
telemt_user_unique_ips_current{user="hello"} 1280
telemt_user_unique_ips_recent_window{user="hello"} 554
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 45605.0 (12h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5159199
telemt_connections_bad_total 274569
telemt_connections_current 5810
telemt_connections_me_current 5810
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 217843
telemt_upstream_connect_attempt_total 44750
telemt_upstream_connect_success_total 42743
telemt_upstream_connect_fail_total 1377
telemt_upstream_connect_attempts_per_request{bucket="1"} 44120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1377
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 2472
telemt_me_reconnect_success_total 878
telemt_me_reader_eof_total 616
telemt_me_idle_close_by_peer_total 615
telemt_me_route_drop_no_conn_total 8184627
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4343485
telemt_me_endpoint_quarantine_total 354
telemt_me_single_endpoint_outage_enter_total 43
telemt_me_single_endpoint_outage_exit_total 43
telemt_me_single_endpoint_outage_reconnect_attempt_total 85
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 85
telemt_me_single_endpoint_shadow_rotate_total 358
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
telemt_me_writers_active_current 127
telemt_desync_total 9184
telemt_desync_full_logged_total 3051
telemt_desync_suppressed_total 6133
telemt_desync_frames_bucket_total{bucket="1_2"} 2028
telemt_desync_frames_bucket_total{bucket="3_10"} 3951
telemt_desync_frames_bucket_total{bucket="gt_10"} 3205
telemt_pool_swap_total 46
telemt_pool_force_close_total 1353
telemt_me_writer_close_signal_drop_total 241
telemt_me_draining_writers_reap_progress_total 15483
telemt_me_writer_removed_unexpected_total 841
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1878
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14402
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1228
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 125
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14130
telemt_me_writer_teardown_success_total{mode="normal"} 16280
telemt_me_writer_teardown_noop_total 15489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 29577
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 30332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 30852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 31375
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 31661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 31762
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 31769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 31769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 31769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 31769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 31769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 31769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 31769
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 31.871514
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 31769
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 241
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 609
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 224
telemt_user_connections_total{user="hello"} 4365519
telemt_user_connections_current{user="hello"} 5810
telemt_user_octets_from_client{user="hello"} 44659811870 (41.59 GB)
telemt_user_octets_to_client{user="hello"} 554408487030 (516.33 GB)
telemt_user_msgs_from_client{user="hello"} 103363
telemt_user_msgs_to_client{user="hello"} 429893
telemt_user_unique_ips_current{user="hello"} 1950
telemt_user_unique_ips_recent_window{user="hello"} 970
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 45572.6 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1858218
telemt_connections_bad_total 239531
telemt_connections_current 3371
telemt_connections_me_current 3371
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 35615
telemt_upstream_connect_attempt_total 20357
telemt_upstream_connect_success_total 20155
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 20338
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10322
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_reconnect_attempts_total 1877
telemt_me_reconnect_success_total 581
telemt_me_reader_eof_total 587
telemt_me_idle_close_by_peer_total 587
telemt_me_route_drop_no_conn_total 535428
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1385809
telemt_me_endpoint_quarantine_total 284
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 361
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
telemt_me_writers_active_current 48
telemt_desync_total 6274
telemt_desync_full_logged_total 2283
telemt_desync_suppressed_total 3991
telemt_desync_frames_bucket_total{bucket="1_2"} 1227
telemt_desync_frames_bucket_total{bucket="3_10"} 2538
telemt_desync_frames_bucket_total{bucket="gt_10"} 2509
telemt_pool_swap_total 48
telemt_pool_force_close_total 1248
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 86
telemt_me_draining_writers_reap_progress_total 16854
telemt_me_writer_removed_unexpected_total 564
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1483
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15958
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1170
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15606
telemt_me_writer_teardown_success_total{mode="normal"} 17441
telemt_me_writer_teardown_noop_total 16854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34181
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34295
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34295
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.523669
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34295
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 86
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 484
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 1382552
telemt_user_connections_current{user="hello"} 3371
telemt_user_octets_from_client{user="hello"} 24965423200 (23.25 GB)
telemt_user_octets_to_client{user="hello"} 641601875118 (597.54 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1336
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 45567.3 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2524906
telemt_connections_bad_total 149061
telemt_connections_current 3377
telemt_connections_me_current 3377
telemt_handshake_timeouts_total 997290
telemt_upstream_connect_attempt_total 19140
telemt_upstream_connect_success_total 19106
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 19109
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 280
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 508
telemt_me_reconnect_success_total 289
telemt_me_reader_eof_total 290
telemt_me_idle_close_by_peer_total 290
telemt_me_route_drop_no_conn_total 475154
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1225537
telemt_me_endpoint_quarantine_total 358
telemt_me_single_endpoint_shadow_rotate_total 363
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
telemt_me_writers_active_current 43
telemt_desync_total 6061
telemt_desync_full_logged_total 2148
telemt_desync_suppressed_total 3913
telemt_desync_frames_bucket_total{bucket="1_2"} 1075
telemt_desync_frames_bucket_total{bucket="3_10"} 2439
telemt_desync_frames_bucket_total{bucket="gt_10"} 2547
telemt_pool_swap_total 50
telemt_pool_force_close_total 1212
telemt_me_writer_close_signal_drop_total 89
telemt_me_draining_writers_reap_progress_total 17162
telemt_me_writer_removed_unexpected_total 280
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1072
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16389
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1195
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 17
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15950
telemt_me_writer_teardown_success_total{mode="normal"} 17461
telemt_me_writer_teardown_noop_total 17162
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34480
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34580
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34623
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.825329
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34623
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 89
telemt_me_refill_failed_total 11
telemt_me_writer_restored_same_endpoint_total 256
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 1221417
telemt_user_connections_current{user="hello"} 3377
telemt_user_octets_from_client{user="hello"} 21460144480 (19.99 GB)
telemt_user_octets_to_client{user="hello"} 610345293512 (568.43 GB)
telemt_user_unique_ips_current{user="hello"} 1340
telemt_user_unique_ips_recent_window{user="hello"} 501
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 43558.5 (12h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537572
telemt_connections_bad_total 19587
telemt_connections_current 603
telemt_connections_me_current 603
telemt_handshake_timeouts_total 192601
telemt_upstream_connect_attempt_total 21447
telemt_upstream_connect_success_total 21445
telemt_upstream_connect_attempts_per_request{bucket="1"} 21445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8952
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12442
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 906
telemt_me_reconnect_success_total 355
telemt_me_reader_eof_total 352
telemt_me_idle_close_by_peer_total 352
telemt_me_route_drop_no_conn_total 115482
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 285041
telemt_me_endpoint_quarantine_total 426
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 375
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
telemt_me_writers_active_current 42
telemt_desync_total 1783
telemt_desync_full_logged_total 724
telemt_desync_suppressed_total 1059
telemt_desync_frames_bucket_total{bucket="1_2"} 352
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 715
telemt_pool_swap_total 48
telemt_pool_force_close_total 1034
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 64
telemt_me_draining_writers_reap_progress_total 19142
telemt_me_writer_removed_unexpected_total 333
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1378
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18101
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1032
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18108
telemt_me_writer_teardown_success_total{mode="normal"} 19479
telemt_me_writer_teardown_noop_total 19142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38308
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38602
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38621
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.771668
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38621
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 64
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 289
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 285206
telemt_user_connections_current{user="hello"} 603
telemt_user_octets_from_client{user="hello"} 4073225351 (3.79 GB)
telemt_user_octets_to_client{user="hello"} 112810713753 (105.06 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 251
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 45576.8 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1909470
telemt_connections_bad_total 166943
telemt_connections_current 3630
telemt_connections_me_current 3630
telemt_handshake_timeouts_total 48418
telemt_upstream_connect_attempt_total 19826
telemt_upstream_connect_success_total 19739
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 19796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9829
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 733
telemt_me_reconnect_success_total 424
telemt_me_reader_eof_total 392
telemt_me_idle_close_by_peer_total 392
telemt_me_route_drop_no_conn_total 464141
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1507335
telemt_me_endpoint_quarantine_total 359
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 361
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
telemt_me_writers_active_current 46
telemt_desync_total 6020
telemt_desync_full_logged_total 2025
telemt_desync_suppressed_total 3995
telemt_desync_frames_bucket_total{bucket="1_2"} 1478
telemt_desync_frames_bucket_total{bucket="3_10"} 2268
telemt_desync_frames_bucket_total{bucket="gt_10"} 2274
telemt_pool_swap_total 50
telemt_pool_force_close_total 1226
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 113
telemt_me_draining_writers_reap_progress_total 17868
telemt_me_writer_removed_unexpected_total 391
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1313
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16955
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1203
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16642
telemt_me_writer_teardown_success_total{mode="normal"} 18268
telemt_me_writer_teardown_noop_total 17868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 36136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 36136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 36136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 36136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 36136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 36136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 36136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 36136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 36136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 36136
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.351629
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 36136
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 113
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 380
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 1501945
telemt_user_connections_current{user="hello"} 3630
telemt_user_octets_from_client{user="hello"} 34133930492 (31.79 GB)
telemt_user_octets_to_client{user="hello"} 701265926220 (653.10 GB)
telemt_user_unique_ips_current{user="hello"} 1306
telemt_user_unique_ips_recent_window{user="hello"} 543
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 45573.9 (12h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1809948
telemt_connections_bad_total 147423
telemt_connections_current 4050
telemt_connections_me_current 4050
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 45045
telemt_upstream_connect_attempt_total 28388
telemt_upstream_connect_success_total 28182
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 28347
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_reconnect_attempts_total 2885
telemt_me_reconnect_success_total 591
telemt_me_reader_eof_total 513
telemt_me_idle_close_by_peer_total 513
telemt_me_seq_mismatch_total 24
telemt_me_route_drop_no_conn_total 480497
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1450101
telemt_me_endpoint_quarantine_total 410
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 359
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
telemt_me_writers_active_current 90
telemt_desync_total 5664
telemt_desync_full_logged_total 1872
telemt_desync_suppressed_total 3792
telemt_desync_frames_bucket_total{bucket="1_2"} 1568
telemt_desync_frames_bucket_total{bucket="3_10"} 2085
telemt_desync_frames_bucket_total{bucket="gt_10"} 2011
telemt_pool_swap_total 49
telemt_pool_force_close_total 1177
telemt_me_writer_close_signal_drop_total 101
telemt_me_draining_writers_reap_progress_total 17012
telemt_me_writer_removed_unexpected_total 522
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1563
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15996
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1124
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 53
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15835
telemt_me_writer_teardown_success_total{mode="normal"} 17559
telemt_me_writer_teardown_noop_total 17013
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34569
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34572
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.980975
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34572
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 101
telemt_me_refill_failed_total 130
telemt_me_writer_restored_same_endpoint_total 456
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1454121
telemt_user_connections_current{user="hello"} 4050
telemt_user_octets_from_client{user="hello"} 22741481267 (21.18 GB)
telemt_user_octets_to_client{user="hello"} 646850458635 (602.43 GB)
telemt_user_msgs_from_client{user="hello"} 40992
telemt_user_msgs_to_client{user="hello"} 110751
telemt_user_unique_ips_current{user="hello"} 1536
telemt_user_unique_ips_recent_window{user="hello"} 550
```