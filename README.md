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

# Server Metrics 2026-03-21 14:27:06 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 64272.4 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2216770
telemt_connections_bad_total 108906
telemt_connections_current 1531
telemt_connections_me_current 1531
telemt_handshake_timeouts_total 75036
telemt_upstream_connect_attempt_total 24746
telemt_upstream_connect_success_total 24621
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 24703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8710
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 31
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 53
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1447
telemt_me_reconnect_success_total 618
telemt_me_reader_eof_total 591
telemt_me_idle_close_by_peer_total 591
telemt_me_route_drop_no_conn_total 1887830
telemt_me_route_drop_channel_closed_total 595
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1770441
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 450
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 506
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
telemt_me_writers_active_current 46
telemt_desync_total 6973
telemt_desync_full_logged_total 2384
telemt_desync_suppressed_total 4589
telemt_desync_frames_bucket_total{bucket="1_2"} 1554
telemt_desync_frames_bucket_total{bucket="3_10"} 2664
telemt_desync_frames_bucket_total{bucket="gt_10"} 2755
telemt_pool_swap_total 69
telemt_pool_force_close_total 2119
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 453
telemt_me_draining_writers_reap_progress_total 22148
telemt_me_writer_removed_unexpected_total 573
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1864
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20646
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2010
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 109
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20029
telemt_me_writer_teardown_success_total{mode="normal"} 22510
telemt_me_writer_teardown_noop_total 22154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38671
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43622
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44664
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 203.968505
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44664
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 453
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 540
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 1769053
telemt_user_connections_current{user="hello"} 1531
telemt_user_octets_from_client{user="hello"} 25506014755 (23.75 GB)
telemt_user_octets_to_client{user="hello"} 440975979351 (410.69 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 572
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 3825.7 (1h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307840
telemt_connections_bad_total 10644
telemt_connections_current 3073
telemt_connections_me_current 3073
telemt_handshake_timeouts_total 9631
telemt_upstream_connect_attempt_total 1456
telemt_upstream_connect_success_total 1449
telemt_upstream_connect_attempts_per_request{bucket="1"} 1449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 749
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 680
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 111
telemt_me_reconnect_success_total 27
telemt_me_reader_eof_total 25
telemt_me_idle_close_by_peer_total 25
telemt_me_route_drop_no_conn_total 203151
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 274677
telemt_me_endpoint_quarantine_total 27
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 33
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
telemt_me_writers_active_current 44
telemt_desync_total 1101
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 657
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 433
telemt_desync_frames_bucket_total{bucket="gt_10"} 446
telemt_pool_swap_total 4
telemt_pool_force_close_total 112
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 1041
telemt_me_writer_removed_unexpected_total 23
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 80
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 986
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 107
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 929
telemt_me_writer_teardown_success_total{mode="normal"} 1066
telemt_me_writer_teardown_noop_total 1041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 2002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 2067
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 2074
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 2107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 2107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 2107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 2107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 2107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 2107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 2107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 2107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 2107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 2107
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.728798
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 2107
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 5
telemt_me_writer_restored_same_endpoint_total 17
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 268497
telemt_user_connections_current{user="hello"} 3073
telemt_user_octets_from_client{user="hello"} 4698043163 (4.38 GB)
telemt_user_octets_to_client{user="hello"} 68088387895 (63.41 GB)
telemt_user_msgs_from_client{user="hello"} 423
telemt_user_msgs_to_client{user="hello"} 734
telemt_user_unique_ips_current{user="hello"} 1493
telemt_user_unique_ips_recent_window{user="hello"} 577
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 64270.4 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4371701
telemt_connections_bad_total 406046
telemt_connections_current 3926
telemt_connections_me_current 3926
telemt_handshake_timeouts_total 163894
telemt_upstream_connect_attempt_total 24192
telemt_upstream_connect_success_total 24147
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 24152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10912
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13138
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 91
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 985
telemt_me_reconnect_success_total 549
telemt_me_reader_eof_total 550
telemt_me_idle_close_by_peer_total 550
telemt_me_route_drop_no_conn_total 2378506
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3552827
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 490
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
telemt_me_writers_active_current 42
telemt_desync_total 14752
telemt_desync_full_logged_total 4975
telemt_desync_suppressed_total 9777
telemt_desync_frames_bucket_total{bucket="1_2"} 3131
telemt_desync_frames_bucket_total{bucket="3_10"} 5804
telemt_desync_frames_bucket_total{bucket="gt_10"} 5817
telemt_pool_swap_total 68
telemt_pool_force_close_total 2195
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 343
telemt_me_draining_writers_reap_progress_total 21959
telemt_me_writer_removed_unexpected_total 531
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1917
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20364
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2003
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19764
telemt_me_writer_teardown_success_total{mode="normal"} 22281
telemt_me_writer_teardown_noop_total 21988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44269
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 70.914579
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44269
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 343
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 499
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 3548425
telemt_user_connections_current{user="hello"} 3926
telemt_user_octets_from_client{user="hello"} 57506891696 (53.56 GB)
telemt_user_octets_to_client{user="hello"} 1194855551060 (1.09 TB)
telemt_user_unique_ips_current{user="hello"} 1469
telemt_user_unique_ips_recent_window{user="hello"} 664
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 64271.5 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3562282
telemt_connections_bad_total 396326
telemt_connections_current 3799
telemt_connections_me_current 3799
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 131099
telemt_upstream_connect_attempt_total 28515
telemt_upstream_connect_success_total 28237
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 28373
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14620
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 481
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1189
telemt_me_reconnect_success_total 556
telemt_me_reader_eof_total 523
telemt_me_idle_close_by_peer_total 523
telemt_me_route_drop_no_conn_total 1109240
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2586832
telemt_me_endpoint_quarantine_total 416
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 493
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
telemt_me_writers_active_current 44
telemt_desync_total 11907
telemt_desync_full_logged_total 4034
telemt_desync_suppressed_total 7873
telemt_desync_frames_bucket_total{bucket="1_2"} 2987
telemt_desync_frames_bucket_total{bucket="3_10"} 4588
telemt_desync_frames_bucket_total{bucket="gt_10"} 4332
telemt_pool_swap_total 70
telemt_pool_force_close_total 2006
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 183
telemt_me_draining_writers_reap_progress_total 21122
telemt_me_writer_removed_unexpected_total 507
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19848
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1872
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 134
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19116
telemt_me_writer_teardown_success_total{mode="normal"} 21636
telemt_me_writer_teardown_noop_total 21123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42759
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.790480
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42759
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 183
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 469
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 2586995
telemt_user_connections_current{user="hello"} 3799
telemt_user_octets_from_client{user="hello"} 48323049561 (45.00 GB)
telemt_user_octets_to_client{user="hello"} 1208657897151 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1438
telemt_user_unique_ips_recent_window{user="hello"} 523
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 64235.4 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3466333
telemt_connections_bad_total 370618
telemt_connections_current 3292
telemt_connections_me_current 3292
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 102697
telemt_upstream_connect_attempt_total 33743
telemt_upstream_connect_success_total 33511
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 33644
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17886
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14494
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 283
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 848
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1292
telemt_me_reconnect_success_total 630
telemt_me_reader_eof_total 574
telemt_me_idle_close_by_peer_total 574
telemt_me_route_drop_no_conn_total 1064610
telemt_me_route_drop_channel_closed_total 32
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2545051
telemt_me_endpoint_quarantine_total 467
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 485
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
telemt_desync_total 11925
telemt_desync_full_logged_total 3977
telemt_desync_suppressed_total 7948
telemt_desync_frames_bucket_total{bucket="1_2"} 3005
telemt_desync_frames_bucket_total{bucket="3_10"} 4482
telemt_desync_frames_bucket_total{bucket="gt_10"} 4438
telemt_pool_swap_total 68
telemt_pool_force_close_total 1941
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 220
telemt_me_draining_writers_reap_progress_total 22486
telemt_me_writer_removed_unexpected_total 547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1901
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21167
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1767
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20545
telemt_me_writer_teardown_success_total{mode="normal"} 23068
telemt_me_writer_teardown_noop_total 22491
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45091
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45284
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45550
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45559
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.758535
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45559
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 220
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 549
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2549258
telemt_user_connections_current{user="hello"} 3292
telemt_user_octets_from_client{user="hello"} 55291242429 (51.49 GB)
telemt_user_octets_to_client{user="hello"} 1198911929068 (1.09 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1314
telemt_user_unique_ips_recent_window{user="hello"} 502
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 64275.0 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11860153
telemt_connections_bad_total 786751
telemt_connections_current 5348
telemt_connections_me_current 5348
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 370517
telemt_upstream_connect_attempt_total 114897
telemt_upstream_connect_success_total 105038
telemt_upstream_connect_fail_total 8843
telemt_upstream_connect_attempts_per_request{bucket="1"} 113881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 73897
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5357
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8843
telemt_me_keepalive_timeout_total 74
telemt_me_reconnect_attempts_total 3822
telemt_me_reconnect_success_total 1361
telemt_me_reader_eof_total 948
telemt_me_idle_close_by_peer_total 947
telemt_me_route_drop_no_conn_total 22063221
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9719071
telemt_me_endpoint_quarantine_total 502
telemt_me_single_endpoint_outage_enter_total 77
telemt_me_single_endpoint_outage_exit_total 77
telemt_me_single_endpoint_outage_reconnect_attempt_total 173
telemt_me_single_endpoint_outage_reconnect_success_total 37
telemt_me_single_endpoint_quarantine_bypass_total 173
telemt_me_single_endpoint_shadow_rotate_total 503
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
telemt_me_writers_active_current 43
telemt_desync_total 17792
telemt_desync_full_logged_total 5622
telemt_desync_suppressed_total 12170
telemt_desync_frames_bucket_total{bucket="1_2"} 3895
telemt_desync_frames_bucket_total{bucket="3_10"} 7764
telemt_desync_frames_bucket_total{bucket="gt_10"} 6133
telemt_pool_swap_total 65
telemt_pool_force_close_total 2102
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 453
telemt_me_draining_writers_reap_progress_total 20822
telemt_me_writer_removed_unexpected_total 1310
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2776
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19166
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1753
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 349
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18720
telemt_me_writer_teardown_success_total{mode="normal"} 21942
telemt_me_writer_teardown_noop_total 20832
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38781
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41995
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42755
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42774
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 165.653851
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42774
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 453
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 945
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 97
telemt_me_writer_removed_unexpected_minus_restored_total 356
telemt_user_connections_total{user="hello"} 9795355
telemt_user_connections_current{user="hello"} 5348
telemt_user_octets_from_client{user="hello"} 71532781617 (66.62 GB)
telemt_user_octets_to_client{user="hello"} 761392915341 (709.10 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 1933
telemt_user_unique_ips_recent_window{user="hello"} 998
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 64242.2 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3488877
telemt_connections_bad_total 389874
telemt_connections_current 3284
telemt_connections_me_current 3284
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 76922
telemt_upstream_connect_attempt_total 27436
telemt_upstream_connect_success_total 27134
telemt_upstream_connect_fail_total 260
telemt_upstream_connect_attempts_per_request{bucket="1"} 27394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12967
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14096
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 260
telemt_me_reconnect_attempts_total 2664
telemt_me_reconnect_success_total 962
telemt_me_reader_eof_total 955
telemt_me_idle_close_by_peer_total 955
telemt_me_route_drop_no_conn_total 1426264
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2677730
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 486
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
telemt_me_writers_active_current 44
telemt_desync_total 12754
telemt_desync_full_logged_total 4437
telemt_desync_suppressed_total 8317
telemt_desync_frames_bucket_total{bucket="1_2"} 2470
telemt_desync_frames_bucket_total{bucket="3_10"} 5077
telemt_desync_frames_bucket_total{bucket="gt_10"} 5207
telemt_pool_swap_total 64
telemt_pool_force_close_total 1860
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 183
telemt_me_draining_writers_reap_progress_total 22979
telemt_me_writer_removed_unexpected_total 927
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2262
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21674
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1612
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21119
telemt_me_writer_teardown_success_total{mode="normal"} 23936
telemt_me_writer_teardown_noop_total 22980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46916
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46916
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.194880
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46916
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 183
telemt_me_refill_failed_total 93
telemt_me_writer_restored_same_endpoint_total 823
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 2661629
telemt_user_connections_current{user="hello"} 3284
telemt_user_octets_from_client{user="hello"} 61513633120 (57.29 GB)
telemt_user_octets_to_client{user="hello"} 1134476265062 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1285
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 1078.0 (0h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 177874
telemt_connections_bad_total 3706
telemt_connections_current 3791
telemt_connections_me_current 3791
telemt_handshake_timeouts_total 92847
telemt_upstream_connect_attempt_total 423
telemt_upstream_connect_success_total 404
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 421
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 195
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 197
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_reconnect_attempts_total 26
telemt_me_reconnect_success_total 29
telemt_me_reader_eof_total 25
telemt_me_idle_close_by_peer_total 25
telemt_me_route_drop_no_conn_total 51752
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73448
telemt_me_endpoint_quarantine_total 2
telemt_me_single_endpoint_shadow_rotate_total 11
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_me_writers_active_current 69
telemt_me_writers_warm_current 19
telemt_desync_total 332
telemt_desync_full_logged_total 108
telemt_desync_suppressed_total 224
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 126
telemt_me_writer_close_signal_drop_total 1
telemt_me_draining_writers_reap_progress_total 230
telemt_me_writer_removed_unexpected_total 26
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 32
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 224
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 230
telemt_me_writer_teardown_success_total{mode="normal"} 256
telemt_me_writer_teardown_noop_total 230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 486
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.001846
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 486
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1
telemt_me_writer_restored_same_endpoint_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 73471
telemt_user_connections_current{user="hello"} 3791
telemt_user_octets_from_client{user="hello"} 870740556 (830.40 MB)
telemt_user_octets_to_client{user="hello"} 29381648996 (27.36 GB)
telemt_user_unique_ips_current{user="hello"} 1546
telemt_user_unique_ips_recent_window{user="hello"} 566
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 62228.2 (17h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1133699
telemt_connections_bad_total 135943
telemt_connections_current 776
telemt_connections_me_current 776
telemt_handshake_timeouts_total 400884
telemt_upstream_connect_attempt_total 29087
telemt_upstream_connect_success_total 29082
telemt_upstream_connect_attempts_per_request{bucket="1"} 29082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11971
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17021
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1227
telemt_me_reconnect_success_total 478
telemt_me_reader_eof_total 476
telemt_me_idle_close_by_peer_total 476
telemt_me_route_drop_no_conn_total 241979
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 525561
telemt_me_endpoint_quarantine_total 570
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 522
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
telemt_desync_total 3382
telemt_desync_full_logged_total 1247
telemt_desync_suppressed_total 2135
telemt_desync_frames_bucket_total{bucket="1_2"} 614
telemt_desync_frames_bucket_total{bucket="3_10"} 1211
telemt_desync_frames_bucket_total{bucket="gt_10"} 1557
telemt_pool_swap_total 69
telemt_pool_force_close_total 1553
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 108
telemt_me_draining_writers_reap_progress_total 26057
telemt_me_writer_removed_unexpected_total 449
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1909
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24609
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1550
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24504
telemt_me_writer_teardown_success_total{mode="normal"} 26518
telemt_me_writer_teardown_noop_total 26057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 51981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 52412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52567
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52575
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.548944
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52575
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 108
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 389
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 525307
telemt_user_connections_current{user="hello"} 776
telemt_user_octets_from_client{user="hello"} 10786881479 (10.05 GB)
telemt_user_octets_to_client{user="hello"} 199656237613 (185.94 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 317
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 64246.6 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3821970
telemt_connections_bad_total 351263
telemt_connections_current 4082
telemt_connections_me_current 4082
telemt_handshake_timeouts_total 120667
telemt_upstream_connect_attempt_total 25944
telemt_upstream_connect_success_total 25836
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 25911
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12857
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 33
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_reconnect_attempts_total 1053
telemt_me_reconnect_success_total 588
telemt_me_reader_eof_total 549
telemt_me_idle_close_by_peer_total 549
telemt_me_route_drop_no_conn_total 1152339
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3033366
telemt_me_endpoint_quarantine_total 478
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 494
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
telemt_desync_total 11978
telemt_desync_full_logged_total 3966
telemt_desync_suppressed_total 8012
telemt_desync_frames_bucket_total{bucket="1_2"} 2838
telemt_desync_frames_bucket_total{bucket="3_10"} 4471
telemt_desync_frames_bucket_total{bucket="gt_10"} 4669
telemt_pool_swap_total 71
telemt_pool_force_close_total 1848
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 202
telemt_me_draining_writers_reap_progress_total 23304
telemt_me_writer_removed_unexpected_total 539
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1835
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22008
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1812
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21456
telemt_me_writer_teardown_success_total{mode="normal"} 23843
telemt_me_writer_teardown_noop_total 23304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46476
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 46903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 46991
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 47103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47147
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.404563
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47147
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 202
telemt_me_refill_failed_total 23
telemt_me_writer_restored_same_endpoint_total 520
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 3025428
telemt_user_connections_current{user="hello"} 4082
telemt_user_octets_from_client{user="hello"} 62706750668 (58.40 GB)
telemt_user_octets_to_client{user="hello"} 1426342451780 (1.30 TB)
telemt_user_unique_ips_current{user="hello"} 1350
telemt_user_unique_ips_recent_window{user="hello"} 665
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 64244.7 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3423717
telemt_connections_bad_total 301451
telemt_connections_current 4788
telemt_connections_me_current 4788
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 99113
telemt_upstream_connect_attempt_total 42231
telemt_upstream_connect_success_total 41945
telemt_upstream_connect_fail_total 235
telemt_upstream_connect_attempts_per_request{bucket="1"} 42180
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14700
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 595
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 235
telemt_me_reconnect_attempts_total 3624
telemt_me_reconnect_success_total 803
telemt_me_reader_eof_total 709
telemt_me_idle_close_by_peer_total 709
telemt_me_seq_mismatch_total 31
telemt_me_route_drop_no_conn_total 1226532
telemt_me_route_drop_channel_closed_total 89
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2753204
telemt_me_endpoint_quarantine_total 536
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 493
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
telemt_me_writers_active_current 89
telemt_desync_total 10623
telemt_desync_full_logged_total 3621
telemt_desync_suppressed_total 7002
telemt_desync_frames_bucket_total{bucket="1_2"} 2661
telemt_desync_frames_bucket_total{bucket="3_10"} 3928
telemt_desync_frames_bucket_total{bucket="gt_10"} 4034
telemt_pool_swap_total 69
telemt_pool_force_close_total 1769
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 193
telemt_me_draining_writers_reap_progress_total 22460
telemt_me_writer_removed_unexpected_total 722
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2183
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21030
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1648
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20691
telemt_me_writer_teardown_success_total{mode="normal"} 23213
telemt_me_writer_teardown_noop_total 22461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45665
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45674
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.473891
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45674
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 193
telemt_me_refill_failed_total 160
telemt_me_writer_restored_same_endpoint_total 623
telemt_me_writer_restored_fallback_total 40
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 2762119
telemt_user_connections_current{user="hello"} 4788
telemt_user_octets_from_client{user="hello"} 49955453073 (46.52 GB)
telemt_user_octets_to_client{user="hello"} 1189069402824 (1.08 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1774
telemt_user_unique_ips_recent_window{user="hello"} 535
```