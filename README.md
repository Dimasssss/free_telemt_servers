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

# Server Metrics 2026-03-21 16:24:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 71300.5 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2550830
telemt_connections_bad_total 152503
telemt_connections_current 1059
telemt_connections_me_current 1059
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 80522
telemt_upstream_connect_attempt_total 30083
telemt_upstream_connect_success_total 29952
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 30040
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12410
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17450
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 59
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1739
telemt_me_reconnect_success_total 683
telemt_me_reader_eof_total 656
telemt_me_idle_close_by_peer_total 656
telemt_me_route_drop_no_conn_total 2152125
telemt_me_route_drop_channel_closed_total 673
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2031787
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 492
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 554
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
telemt_me_writers_active_current 45
telemt_desync_total 8111
telemt_desync_full_logged_total 2802
telemt_desync_suppressed_total 5309
telemt_desync_frames_bucket_total{bucket="1_2"} 1776
telemt_desync_frames_bucket_total{bucket="3_10"} 3082
telemt_desync_frames_bucket_total{bucket="gt_10"} 3253
telemt_pool_swap_total 77
telemt_pool_force_close_total 2334
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 526
telemt_me_draining_writers_reap_progress_total 24190
telemt_me_writer_removed_unexpected_total 634
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2085
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22523
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2210
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21856
telemt_me_writer_teardown_success_total{mode="normal"} 24608
telemt_me_writer_teardown_noop_total 24197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47651
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48805
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48805
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 228.978369
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48805
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 526
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 584
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2033100
telemt_user_connections_current{user="hello"} 1059
telemt_user_octets_from_client{user="hello"} 28751805857 (26.78 GB)
telemt_user_octets_to_client{user="hello"} 504411937582 (469.77 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 339
telemt_user_unique_ips_recent_window{user="hello"} 343
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 2426.3 (0h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103508
telemt_connections_bad_total 4565
telemt_connections_current 1187
telemt_connections_me_current 1187
telemt_handshake_timeouts_total 1999
telemt_upstream_connect_attempt_total 997
telemt_upstream_connect_success_total 996
telemt_upstream_connect_attempts_per_request{bucket="1"} 996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 502
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 7
telemt_me_reconnect_success_total 6
telemt_me_reader_eof_total 6
telemt_me_idle_close_by_peer_total 6
telemt_me_route_drop_no_conn_total 82396
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 89455
telemt_me_endpoint_quarantine_total 19
telemt_me_single_endpoint_shadow_rotate_total 24
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
telemt_me_writers_active_current 43
telemt_desync_total 271
telemt_desync_full_logged_total 151
telemt_desync_suppressed_total 120
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 2
telemt_pool_force_close_total 27
telemt_me_writer_close_signal_drop_total 18
telemt_me_draining_writers_reap_progress_total 861
telemt_me_writer_removed_unexpected_total 6
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 62
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 805
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 27
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 834
telemt_me_writer_teardown_success_total{mode="normal"} 867
telemt_me_writer_teardown_noop_total 861
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 1715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 1726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 1728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 1728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 1728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 1728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 1728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 1728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 1728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 1728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 1728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 1728
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 1728
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.061700
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 1728
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 18
telemt_me_writer_restored_same_endpoint_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 89019
telemt_user_connections_current{user="hello"} 1187
telemt_user_octets_from_client{user="hello"} 776513320 (740.54 MB)
telemt_user_octets_to_client{user="hello"} 17709097468 (16.49 GB)
telemt_user_unique_ips_current{user="hello"} 447
telemt_user_unique_ips_recent_window{user="hello"} 193
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 71298.9 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5253545
telemt_connections_bad_total 449191
telemt_connections_current 4344
telemt_connections_me_current 4344
telemt_handshake_timeouts_total 177678
telemt_upstream_connect_attempt_total 26266
telemt_upstream_connect_success_total 26210
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 26216
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11778
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14323
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1173
telemt_me_reconnect_success_total 595
telemt_me_reader_eof_total 599
telemt_me_idle_close_by_peer_total 599
telemt_me_route_drop_no_conn_total 3199635
telemt_me_route_drop_channel_closed_total 47
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4319584
telemt_me_endpoint_quarantine_total 445
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 534
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
telemt_me_writers_active_current 44
telemt_desync_total 17709
telemt_desync_full_logged_total 5942
telemt_desync_suppressed_total 11767
telemt_desync_frames_bucket_total{bucket="1_2"} 3721
telemt_desync_frames_bucket_total{bucket="3_10"} 7041
telemt_desync_frames_bucket_total{bucket="gt_10"} 6947
telemt_pool_swap_total 76
telemt_pool_force_close_total 2498
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 396
telemt_me_draining_writers_reap_progress_total 23870
telemt_me_writer_removed_unexpected_total 579
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2095
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22079
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2294
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 204
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21372
telemt_me_writer_teardown_success_total{mode="normal"} 24174
telemt_me_writer_teardown_noop_total 23904
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46964
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 47565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48078
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 97.306033
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48078
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 396
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 536
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4314354
telemt_user_connections_current{user="hello"} 4346
telemt_user_octets_from_client{user="hello"} 67869254828 (63.21 GB)
telemt_user_octets_to_client{user="hello"} 1378752037372 (1.25 TB)
telemt_user_unique_ips_current{user="hello"} 1586
telemt_user_unique_ips_recent_window{user="hello"} 815
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 71299.4 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4207998
telemt_connections_bad_total 436264
telemt_connections_current 3189
telemt_connections_me_current 3189
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 146508
telemt_upstream_connect_attempt_total 30655
telemt_upstream_connect_success_total 30367
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 30508
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15553
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14291
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 496
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1401
telemt_me_reconnect_success_total 620
telemt_me_reader_eof_total 584
telemt_me_idle_close_by_peer_total 584
telemt_me_route_drop_no_conn_total 1345841
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3108845
telemt_me_endpoint_quarantine_total 451
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 542
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
telemt_me_writers_active_current 43
telemt_desync_total 14852
telemt_desync_full_logged_total 4907
telemt_desync_suppressed_total 9945
telemt_desync_frames_bucket_total{bucket="1_2"} 3683
telemt_desync_frames_bucket_total{bucket="3_10"} 5743
telemt_desync_frames_bucket_total{bucket="gt_10"} 5426
telemt_pool_swap_total 78
telemt_pool_force_close_total 2292
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 235
telemt_me_draining_writers_reap_progress_total 23014
telemt_me_writer_removed_unexpected_total 565
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1990
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21569
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2131
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 161
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20722
telemt_me_writer_teardown_success_total{mode="normal"} 23559
telemt_me_writer_teardown_noop_total 23017
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45892
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46261
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46576
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46576
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 26.260729
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46576
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 235
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 524
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 3108108
telemt_user_connections_current{user="hello"} 3189
telemt_user_octets_from_client{user="hello"} 69871725909 (65.07 GB)
telemt_user_octets_to_client{user="hello"} 1431237259463 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1190
telemt_user_unique_ips_recent_window{user="hello"} 737
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 71263.5 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4152659
telemt_connections_bad_total 421392
telemt_connections_current 4326
telemt_connections_me_current 4326
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 125822
telemt_upstream_connect_attempt_total 35897
telemt_upstream_connect_success_total 35653
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 35786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18861
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15632
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 865
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1463
telemt_me_reconnect_success_total 669
telemt_me_reader_eof_total 612
telemt_me_idle_close_by_peer_total 612
telemt_me_route_drop_no_conn_total 1439341
telemt_me_route_drop_channel_closed_total 42
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3090231
telemt_me_endpoint_quarantine_total 504
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 533
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
telemt_me_writers_active_current 43
telemt_desync_total 14306
telemt_desync_full_logged_total 4709
telemt_desync_suppressed_total 9597
telemt_desync_frames_bucket_total{bucket="1_2"} 3559
telemt_desync_frames_bucket_total{bucket="3_10"} 5391
telemt_desync_frames_bucket_total{bucket="gt_10"} 5356
telemt_pool_swap_total 76
telemt_pool_force_close_total 2178
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 253
telemt_me_draining_writers_reap_progress_total 24378
telemt_me_writer_removed_unexpected_total 582
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2059
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22923
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1993
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 185
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22200
telemt_me_writer_teardown_success_total{mode="normal"} 24982
telemt_me_writer_teardown_noop_total 24384
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49366
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 13.598382
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49366
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 253
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 576
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 3093710
telemt_user_connections_current{user="hello"} 4326
telemt_user_octets_from_client{user="hello"} 75264683345 (70.10 GB)
telemt_user_octets_to_client{user="hello"} 1428568850976 (1.30 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1685
telemt_user_unique_ips_recent_window{user="hello"} 695
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 71302.6 (19h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 14323723
telemt_connections_bad_total 923338
telemt_connections_current 5066
telemt_connections_me_current 5066
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 421683
telemt_upstream_connect_attempt_total 117027
telemt_upstream_connect_success_total 107094
telemt_upstream_connect_fail_total 8859
telemt_upstream_connect_attempts_per_request{bucket="1"} 115953
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26136
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8859
telemt_me_keepalive_timeout_total 190
telemt_me_reconnect_attempts_total 3904
telemt_me_reconnect_success_total 1428
telemt_me_reader_eof_total 998
telemt_me_idle_close_by_peer_total 997
telemt_me_route_drop_no_conn_total 28319472
telemt_me_route_drop_channel_closed_total 92
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11821795
telemt_me_endpoint_quarantine_total 541
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 557
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 20920
telemt_desync_full_logged_total 6453
telemt_desync_suppressed_total 14467
telemt_desync_frames_bucket_total{bucket="1_2"} 4564
telemt_desync_frames_bucket_total{bucket="3_10"} 9157
telemt_desync_frames_bucket_total{bucket="gt_10"} 7199
telemt_pool_swap_total 73
telemt_pool_force_close_total 2391
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 523
telemt_me_draining_writers_reap_progress_total 22695
telemt_me_writer_removed_unexpected_total 1359
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2962
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20870
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 380
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20304
telemt_me_writer_teardown_success_total{mode="normal"} 23832
telemt_me_writer_teardown_noop_total 22707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44488
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 46485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 46520
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 46522
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 46525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 46530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 46530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 46534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 46539
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 177.534139
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 46539
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 523
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 1001
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 11896315
telemt_user_connections_current{user="hello"} 5066
telemt_user_octets_from_client{user="hello"} 89191443957 (83.07 GB)
telemt_user_octets_to_client{user="hello"} 831382492701 (774.29 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 1833
telemt_user_unique_ips_recent_window{user="hello"} 1410
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 71270.1 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4151402
telemt_connections_bad_total 445246
telemt_connections_current 4005
telemt_connections_me_current 4005
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 87912
telemt_upstream_connect_attempt_total 29770
telemt_upstream_connect_success_total 29430
telemt_upstream_connect_fail_total 292
telemt_upstream_connect_attempts_per_request{bucket="1"} 29722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15397
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 81
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 292
telemt_me_reconnect_attempts_total 3017
telemt_me_reconnect_success_total 1064
telemt_me_reader_eof_total 1058
telemt_me_idle_close_by_peer_total 1058
telemt_me_route_drop_no_conn_total 1786143
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3206335
telemt_me_endpoint_quarantine_total 436
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 529
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
telemt_me_writers_active_current 44
telemt_desync_total 15552
telemt_desync_full_logged_total 5392
telemt_desync_suppressed_total 10160
telemt_desync_frames_bucket_total{bucket="1_2"} 3036
telemt_desync_frames_bucket_total{bucket="3_10"} 6164
telemt_desync_frames_bucket_total{bucket="gt_10"} 6352
telemt_pool_swap_total 71
telemt_pool_force_close_total 2076
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 210
telemt_me_draining_writers_reap_progress_total 24975
telemt_me_writer_removed_unexpected_total 1025
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2511
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23525
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1775
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 301
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22899
telemt_me_writer_teardown_success_total{mode="normal"} 26036
telemt_me_writer_teardown_noop_total 24976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50753
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50938
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 51012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 51012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 51012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 51012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 51012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 51012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 51012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 51012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 51012
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.572476
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 51012
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 210
telemt_me_refill_failed_total 107
telemt_me_writer_restored_same_endpoint_total 919
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 3189388
telemt_user_connections_current{user="hello"} 4005
telemt_user_octets_from_client{user="hello"} 83320217268 (77.60 GB)
telemt_user_octets_to_client{user="hello"} 1311726358610 (1.19 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1641
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 8105.7 (2h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1255687
telemt_connections_bad_total 45796
telemt_connections_current 3643
telemt_connections_me_current 3643
telemt_handshake_timeouts_total 582506
telemt_upstream_connect_attempt_total 2764
telemt_upstream_connect_success_total 2715
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 2758
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1487
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_reconnect_attempts_total 380
telemt_me_reconnect_success_total 106
telemt_me_reader_eof_total 97
telemt_me_idle_close_by_peer_total 97
telemt_me_route_drop_no_conn_total 479914
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 577419
telemt_me_endpoint_quarantine_total 32
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 59
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_me_writers_active_current 41
telemt_desync_total 3152
telemt_desync_full_logged_total 983
telemt_desync_suppressed_total 2169
telemt_desync_frames_bucket_total{bucket="1_2"} 610
telemt_desync_frames_bucket_total{bucket="3_10"} 1147
telemt_desync_frames_bucket_total{bucket="gt_10"} 1395
telemt_pool_swap_total 7
telemt_pool_force_close_total 231
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 2342
telemt_me_writer_removed_unexpected_total 98
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 218
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2222
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2111
telemt_me_writer_teardown_success_total{mode="normal"} 2440
telemt_me_writer_teardown_noop_total 2342
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 4679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 4719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4782
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.824267
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4782
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 16
telemt_me_writer_restored_same_endpoint_total 88
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 10
telemt_user_connections_total{user="hello"} 576605
telemt_user_connections_current{user="hello"} 3643
telemt_user_octets_from_client{user="hello"} 14060916340 (13.10 GB)
telemt_user_octets_to_client{user="hello"} 216158748348 (201.31 GB)
telemt_user_unique_ips_current{user="hello"} 1446
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 69256.4 (19h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1317439
telemt_connections_bad_total 146972
telemt_connections_current 749
telemt_connections_me_current 749
telemt_handshake_timeouts_total 468409
telemt_upstream_connect_attempt_total 32035
telemt_upstream_connect_success_total 32027
telemt_upstream_connect_attempts_per_request{bucket="1"} 32027
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13100
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18820
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1365
telemt_me_reconnect_success_total 572
telemt_me_reader_eof_total 571
telemt_me_idle_close_by_peer_total 571
telemt_me_route_drop_no_conn_total 290189
telemt_me_route_drop_channel_closed_total 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 622523
telemt_me_endpoint_quarantine_total 610
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 576
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
telemt_me_writers_active_current 43
telemt_desync_total 3752
telemt_desync_full_logged_total 1343
telemt_desync_suppressed_total 2409
telemt_desync_frames_bucket_total{bucket="1_2"} 713
telemt_desync_frames_bucket_total{bucket="3_10"} 1335
telemt_desync_frames_bucket_total{bucket="gt_10"} 1704
telemt_pool_swap_total 75
telemt_pool_force_close_total 1772
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 28704
telemt_me_writer_removed_unexpected_total 540
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2173
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27088
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1742
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 30
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26932
telemt_me_writer_teardown_success_total{mode="normal"} 29261
telemt_me_writer_teardown_noop_total 28704
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57719
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57894
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57965
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.683322
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57965
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 477
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 622095
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 12852549763 (11.97 GB)
telemt_user_octets_to_client{user="hello"} 241650419645 (225.05 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 306
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 71274.7 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4621067
telemt_connections_bad_total 430098
telemt_connections_current 4929
telemt_connections_me_current 4929
telemt_handshake_timeouts_total 150850
telemt_upstream_connect_attempt_total 28109
telemt_upstream_connect_success_total 27991
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 28073
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14116
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_reconnect_attempts_total 1198
telemt_me_reconnect_success_total 627
telemt_me_reader_eof_total 594
telemt_me_idle_close_by_peer_total 594
telemt_me_route_drop_no_conn_total 1421468
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3655765
telemt_me_endpoint_quarantine_total 511
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 545
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 14253
telemt_desync_full_logged_total 4706
telemt_desync_suppressed_total 9547
telemt_desync_frames_bucket_total{bucket="1_2"} 3372
telemt_desync_frames_bucket_total{bucket="3_10"} 5302
telemt_desync_frames_bucket_total{bucket="gt_10"} 5579
telemt_pool_swap_total 79
telemt_pool_force_close_total 2059
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 241
telemt_me_draining_writers_reap_progress_total 25184
telemt_me_writer_removed_unexpected_total 582
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2019
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23749
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2011
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23125
telemt_me_writer_teardown_success_total{mode="normal"} 25768
telemt_me_writer_teardown_noop_total 25185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50141
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 50673
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50953
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.267818
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50953
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 241
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 556
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3646305
telemt_user_connections_current{user="hello"} 4929
telemt_user_octets_from_client{user="hello"} 73051295312 (68.03 GB)
telemt_user_octets_to_client{user="hello"} 1711062124956 (1.56 TB)
telemt_user_unique_ips_current{user="hello"} 1769
telemt_user_unique_ips_recent_window{user="hello"} 607
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 71271.3 (19h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4086338
telemt_connections_bad_total 369585
telemt_connections_current 3936
telemt_connections_me_current 3936
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 127760
telemt_upstream_connect_attempt_total 44570
telemt_upstream_connect_success_total 44256
telemt_upstream_connect_fail_total 258
telemt_upstream_connect_attempts_per_request{bucket="1"} 44514
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27186
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15951
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 258
telemt_me_reconnect_attempts_total 4043
telemt_me_reconnect_success_total 898
telemt_me_reader_eof_total 777
telemt_me_idle_close_by_peer_total 777
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1492377
telemt_me_route_drop_channel_closed_total 116
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3257295
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 540
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
telemt_desync_total 12712
telemt_desync_full_logged_total 4303
telemt_desync_suppressed_total 8409
telemt_desync_frames_bucket_total{bucket="1_2"} 3172
telemt_desync_frames_bucket_total{bucket="3_10"} 4732
telemt_desync_frames_bucket_total{bucket="gt_10"} 4808
telemt_pool_swap_total 77
telemt_pool_force_close_total 2004
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 224
telemt_me_draining_writers_reap_progress_total 24537
telemt_me_writer_removed_unexpected_total 790
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2422
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22938
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1831
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22533
telemt_me_writer_teardown_success_total{mode="normal"} 25360
telemt_me_writer_teardown_noop_total 24538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49558
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49759
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49898
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49898
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.408559
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49898
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 224
telemt_me_refill_failed_total 179
telemt_me_writer_restored_same_endpoint_total 690
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 3265209
telemt_user_connections_current{user="hello"} 3936
telemt_user_octets_from_client{user="hello"} 59145877785 (55.08 GB)
telemt_user_octets_to_client{user="hello"} 1387042098560 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1572
telemt_user_unique_ips_recent_window{user="hello"} 553
```