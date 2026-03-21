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

# Server Metrics 2026-03-21 10:32:29 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 50196.6 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1453478
telemt_connections_bad_total 74950
telemt_connections_current 1638
telemt_connections_me_current 1638
telemt_handshake_timeouts_total 58512
telemt_upstream_connect_attempt_total 19765
telemt_upstream_connect_success_total 19678
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 19741
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12579
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 14
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 931
telemt_me_reconnect_success_total 405
telemt_me_reader_eof_total 408
telemt_me_idle_close_by_peer_total 408
telemt_me_route_drop_no_conn_total 782599
telemt_me_route_drop_channel_closed_total 300
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1106877
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 349
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 401
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
telemt_me_writers_active_current 50
telemt_desync_total 4680
telemt_desync_full_logged_total 1624
telemt_desync_suppressed_total 3056
telemt_desync_frames_bucket_total{bucket="1_2"} 973
telemt_desync_frames_bucket_total{bucket="3_10"} 1814
telemt_desync_frames_bucket_total{bucket="gt_10"} 1893
telemt_pool_swap_total 54
telemt_pool_force_close_total 1541
telemt_pool_stale_pick_total 12
telemt_me_writer_close_signal_drop_total 247
telemt_me_draining_writers_reap_progress_total 17677
telemt_me_writer_removed_unexpected_total 386
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1422
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16537
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1485
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 56
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16136
telemt_me_writer_teardown_success_total{mode="normal"} 17959
telemt_me_writer_teardown_noop_total 17679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35638
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35638
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 95.414362
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35638
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 247
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1106009
telemt_user_connections_current{user="hello"} 1638
telemt_user_octets_from_client{user="hello"} 15534957287 (14.47 GB)
telemt_user_octets_to_client{user="hello"} 314682939547 (293.07 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 580
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 50198.1 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3723145
telemt_connections_bad_total 378458
telemt_connections_current 4874
telemt_connections_me_current 4874
telemt_handshake_timeouts_total 108584
telemt_upstream_connect_attempt_total 17886
telemt_upstream_connect_success_total 17802
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 17859
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7420
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 1097
telemt_me_reconnect_success_total 410
telemt_me_reader_eof_total 403
telemt_me_idle_close_by_peer_total 402
telemt_me_route_drop_no_conn_total 1626053
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2552771
telemt_me_endpoint_quarantine_total 316
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 385
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
telemt_desync_total 11012
telemt_desync_full_logged_total 3688
telemt_desync_suppressed_total 7324
telemt_desync_frames_bucket_total{bucket="1_2"} 2241
telemt_desync_frames_bucket_total{bucket="3_10"} 4349
telemt_desync_frames_bucket_total{bucket="gt_10"} 4422
telemt_pool_swap_total 54
telemt_pool_force_close_total 1657
telemt_me_writer_close_signal_drop_total 206
telemt_me_draining_writers_reap_progress_total 16001
telemt_me_writer_removed_unexpected_total 377
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1486
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14878
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1559
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 98
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 14344
telemt_me_writer_teardown_success_total{mode="normal"} 16364
telemt_me_writer_teardown_noop_total 16001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 30779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 31419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 31742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 32195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 32351
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 32365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 32365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 32365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 32365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 32365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 32365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 32365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 32365
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 18.232900
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 32365
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 206
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 327
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 2548097
telemt_user_connections_current{user="hello"} 4874
telemt_user_octets_from_client{user="hello"} 35642572468 (33.19 GB)
telemt_user_octets_to_client{user="hello"} 855431464032 (796.68 GB)
telemt_user_unique_ips_current{user="hello"} 1759
telemt_user_unique_ips_recent_window{user="hello"} 706
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 50194.5 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2760636
telemt_connections_bad_total 316122
telemt_connections_current 4255
telemt_connections_me_current 4255
telemt_handshake_timeouts_total 102424
telemt_upstream_connect_attempt_total 19340
telemt_upstream_connect_success_total 19327
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 19328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8752
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 631
telemt_me_reconnect_success_total 360
telemt_me_reader_eof_total 374
telemt_me_idle_close_by_peer_total 374
telemt_me_route_drop_no_conn_total 1136936
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2172687
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 390
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
telemt_me_writers_active_current 44
telemt_desync_total 9465
telemt_desync_full_logged_total 3254
telemt_desync_suppressed_total 6211
telemt_desync_frames_bucket_total{bucket="1_2"} 1965
telemt_desync_frames_bucket_total{bucket="3_10"} 3768
telemt_desync_frames_bucket_total{bucket="gt_10"} 3732
telemt_pool_swap_total 54
telemt_pool_force_close_total 1652
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 222
telemt_me_draining_writers_reap_progress_total 17615
telemt_me_writer_removed_unexpected_total 353
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1435
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16391
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1565
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15963
telemt_me_writer_teardown_success_total{mode="normal"} 17826
telemt_me_writer_teardown_noop_total 17627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 33100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 33905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35280
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35417
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35453
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.832124
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35453
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 222
telemt_me_refill_failed_total 13
telemt_me_writer_restored_same_endpoint_total 323
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 2169412
telemt_user_connections_current{user="hello"} 4255
telemt_user_octets_from_client{user="hello"} 35478498952 (33.04 GB)
telemt_user_octets_to_client{user="hello"} 814580845516 (758.64 GB)
telemt_user_unique_ips_current{user="hello"} 1594
telemt_user_unique_ips_recent_window{user="hello"} 586
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 50195.6 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2280469
telemt_connections_bad_total 255707
telemt_connections_current 3277
telemt_connections_me_current 3277
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 96542
telemt_upstream_connect_attempt_total 24361
telemt_upstream_connect_success_total 24114
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 24241
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 416
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 1033
telemt_me_reconnect_success_total 461
telemt_me_reader_eof_total 426
telemt_me_idle_close_by_peer_total 426
telemt_me_route_drop_no_conn_total 667928
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1597425
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 391
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
telemt_desync_total 7408
telemt_desync_full_logged_total 2539
telemt_desync_suppressed_total 4869
telemt_desync_frames_bucket_total{bucket="1_2"} 1847
telemt_desync_frames_bucket_total{bucket="3_10"} 2911
telemt_desync_frames_bucket_total{bucket="gt_10"} 2650
telemt_pool_swap_total 54
telemt_pool_force_close_total 1480
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 99
telemt_me_draining_writers_reap_progress_total 17482
telemt_me_writer_removed_unexpected_total 419
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1426
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16489
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1393
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 87
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16002
telemt_me_writer_teardown_success_total{mode="normal"} 17915
telemt_me_writer_teardown_noop_total 17483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 35225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 35324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 35376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 35396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 35398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 35398
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.004352
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 35398
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 99
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 386
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 1599225
telemt_user_connections_current{user="hello"} 3277
telemt_user_octets_from_client{user="hello"} 31603566689 (29.43 GB)
telemt_user_octets_to_client{user="hello"} 768760033099 (715.96 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1297
telemt_user_unique_ips_recent_window{user="hello"} 510
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 50159.6 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2222861
telemt_connections_bad_total 248689
telemt_connections_current 3435
telemt_connections_me_current 3435
telemt_handshake_timeouts_total 67916
telemt_upstream_connect_attempt_total 20697
telemt_upstream_connect_success_total 20649
telemt_upstream_connect_attempts_per_request{bucket="1"} 20649
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9294
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11265
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 22
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 719
telemt_me_reconnect_success_total 470
telemt_me_reader_eof_total 435
telemt_me_idle_close_by_peer_total 435
telemt_me_route_drop_no_conn_total 626062
telemt_me_route_drop_channel_closed_total 20
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1596045
telemt_me_endpoint_quarantine_total 378
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 385
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
telemt_desync_total 7493
telemt_desync_full_logged_total 2563
telemt_desync_suppressed_total 4930
telemt_desync_frames_bucket_total{bucket="1_2"} 1989
telemt_desync_frames_bucket_total{bucket="3_10"} 2865
telemt_desync_frames_bucket_total{bucket="gt_10"} 2639
telemt_pool_swap_total 53
telemt_pool_force_close_total 1457
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 136
telemt_me_draining_writers_reap_progress_total 18567
telemt_me_writer_removed_unexpected_total 410
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1429
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17579
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1347
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 110
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17110
telemt_me_writer_teardown_success_total{mode="normal"} 19008
telemt_me_writer_teardown_noop_total 18570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36940
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37559
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37578
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.301969
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37578
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 136
telemt_me_refill_failed_total 14
telemt_me_writer_restored_same_endpoint_total 420
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 33
telemt_user_connections_total{user="hello"} 1593515
telemt_user_connections_current{user="hello"} 3435
telemt_user_octets_from_client{user="hello"} 37395330520 (34.83 GB)
telemt_user_octets_to_client{user="hello"} 779649809264 (726.11 GB)
telemt_user_unique_ips_current{user="hello"} 1329
telemt_user_unique_ips_recent_window{user="hello"} 505
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 50198.8 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6771605
telemt_connections_bad_total 391304
telemt_connections_current 5524
telemt_connections_me_current 5524
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 250638
telemt_upstream_connect_attempt_total 59765
telemt_upstream_connect_success_total 57137
telemt_upstream_connect_fail_total 1925
telemt_upstream_connect_attempts_per_request{bucket="1"} 59062
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40380
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14734
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2023
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1925
telemt_me_keepalive_timeout_total 59
telemt_me_reconnect_attempts_total 2931
telemt_me_reconnect_success_total 1008
telemt_me_reader_eof_total 706
telemt_me_idle_close_by_peer_total 705
telemt_me_route_drop_no_conn_total 11344219
telemt_me_route_drop_channel_closed_total 43
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5691383
telemt_me_endpoint_quarantine_total 392
telemt_me_single_endpoint_outage_enter_total 55
telemt_me_single_endpoint_outage_exit_total 55
telemt_me_single_endpoint_outage_reconnect_attempt_total 117
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 117
telemt_me_single_endpoint_shadow_rotate_total 398
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
telemt_me_writers_active_current 44
telemt_desync_total 11161
telemt_desync_full_logged_total 3591
telemt_desync_suppressed_total 7570
telemt_desync_frames_bucket_total{bucket="1_2"} 2453
telemt_desync_frames_bucket_total{bucket="3_10"} 4862
telemt_desync_frames_bucket_total{bucket="gt_10"} 3846
telemt_pool_swap_total 51
telemt_pool_force_close_total 1607
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 320
telemt_me_draining_writers_reap_progress_total 16836
telemt_me_writer_removed_unexpected_total 970
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2134
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 15583
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1387
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 220
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15229
telemt_me_writer_teardown_success_total{mode="normal"} 17717
telemt_me_writer_teardown_noop_total 16845
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 31811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 32765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 33381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34029
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34562
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34562
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 42.167753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34562
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 320
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 698
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 61
telemt_me_writer_removed_unexpected_minus_restored_total 264
telemt_user_connections_total{user="hello"} 5725745
telemt_user_connections_current{user="hello"} 5524
telemt_user_octets_from_client{user="hello"} 51019627948 (47.52 GB)
telemt_user_octets_to_client{user="hello"} 605240017943 (563.67 GB)
telemt_user_msgs_from_client{user="hello"} 126757
telemt_user_msgs_to_client{user="hello"} 447030
telemt_user_unique_ips_current{user="hello"} 1869
telemt_user_unique_ips_recent_window{user="hello"} 1029
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 50166.4 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2222305
telemt_connections_bad_total 269964
telemt_connections_current 3286
telemt_connections_me_current 3286
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 44012
telemt_upstream_connect_attempt_total 22123
telemt_upstream_connect_success_total 21896
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 22101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10565
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11286
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_reconnect_attempts_total 2107
telemt_me_reconnect_success_total 696
telemt_me_reader_eof_total 706
telemt_me_idle_close_by_peer_total 706
telemt_me_route_drop_no_conn_total 752934
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 29
telemt_me_route_drop_queue_full_profile_total{profile="high"} 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1684107
telemt_me_endpoint_quarantine_total 308
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 386
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
telemt_desync_total 7718
telemt_desync_full_logged_total 2808
telemt_desync_suppressed_total 4910
telemt_desync_frames_bucket_total{bucket="1_2"} 1466
telemt_desync_frames_bucket_total{bucket="3_10"} 3130
telemt_desync_frames_bucket_total{bucket="gt_10"} 3122
telemt_pool_swap_total 51
telemt_pool_force_close_total 1391
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 18363
telemt_me_writer_removed_unexpected_total 683
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1700
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17369
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1250
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 141
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 16972
telemt_me_writer_teardown_success_total{mode="normal"} 19069
telemt_me_writer_teardown_noop_total 18363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37313
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37420
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37432
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.705309
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37432
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 594
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 81
telemt_user_connections_total{user="hello"} 1671313
telemt_user_connections_current{user="hello"} 3286
telemt_user_octets_from_client{user="hello"} 30304385476 (28.22 GB)
telemt_user_octets_to_client{user="hello"} 765624791550 (713.04 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1403
telemt_user_unique_ips_recent_window{user="hello"} 546
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 50161.0 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3216293
telemt_connections_bad_total 175246
telemt_connections_current 3316
telemt_connections_me_current 3316
telemt_handshake_timeouts_total 1343527
telemt_upstream_connect_attempt_total 20573
telemt_upstream_connect_success_total 20539
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 20542
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 543
telemt_me_reconnect_success_total 306
telemt_me_reader_eof_total 310
telemt_me_idle_close_by_peer_total 310
telemt_me_route_drop_no_conn_total 598103
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1499352
telemt_me_endpoint_quarantine_total 378
telemt_me_single_endpoint_shadow_rotate_total 395
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
telemt_me_writers_active_current 46
telemt_desync_total 7386
telemt_desync_full_logged_total 2610
telemt_desync_suppressed_total 4776
telemt_desync_frames_bucket_total{bucket="1_2"} 1312
telemt_desync_frames_bucket_total{bucket="3_10"} 2948
telemt_desync_frames_bucket_total{bucket="gt_10"} 3126
telemt_pool_swap_total 55
telemt_pool_force_close_total 1349
telemt_me_writer_close_signal_drop_total 105
telemt_me_draining_writers_reap_progress_total 18458
telemt_me_writer_removed_unexpected_total 298
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1168
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17609
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1331
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17109
telemt_me_writer_teardown_success_total{mode="normal"} 18777
telemt_me_writer_teardown_noop_total 18458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37190
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37225
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37235
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.958140
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37235
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 105
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 273
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 1494848
telemt_user_connections_current{user="hello"} 3316
telemt_user_octets_from_client{user="hello"} 26757476076 (24.92 GB)
telemt_user_octets_to_client{user="hello"} 733013216936 (682.67 GB)
telemt_user_unique_ips_current{user="hello"} 1335
telemt_user_unique_ips_recent_window{user="hello"} 510
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 48152.7 (13h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 665522
telemt_connections_bad_total 22362
telemt_connections_current 685
telemt_connections_me_current 685
telemt_handshake_timeouts_total 249306
telemt_upstream_connect_attempt_total 23396
telemt_upstream_connect_success_total 23394
telemt_upstream_connect_attempts_per_request{bucket="1"} 23394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13650
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1032
telemt_me_reconnect_success_total 379
telemt_me_reader_eof_total 380
telemt_me_idle_close_by_peer_total 380
telemt_me_route_drop_no_conn_total 141943
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 341641
telemt_me_endpoint_quarantine_total 459
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 413
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
telemt_me_writers_active_current 43
telemt_desync_total 2223
telemt_desync_full_logged_total 882
telemt_desync_suppressed_total 1341
telemt_desync_frames_bucket_total{bucket="1_2"} 378
telemt_desync_frames_bucket_total{bucket="3_10"} 828
telemt_desync_frames_bucket_total{bucket="gt_10"} 1017
telemt_pool_swap_total 53
telemt_pool_force_close_total 1162
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 79
telemt_me_draining_writers_reap_progress_total 20933
telemt_me_writer_removed_unexpected_total 361
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1523
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19775
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19771
telemt_me_writer_teardown_success_total{mode="normal"} 21298
telemt_me_writer_teardown_noop_total 20933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 42231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 42231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 42231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 42231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 42231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 42231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 42231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 42231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 42231
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.226405
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 42231
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 79
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 309
telemt_me_writer_restored_fallback_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 341767
telemt_user_connections_current{user="hello"} 685
telemt_user_octets_from_client{user="hello"} 5027240383 (4.68 GB)
telemt_user_octets_to_client{user="hello"} 131691881501 (122.65 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 281
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 50170.8 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2351214
telemt_connections_bad_total 216315
telemt_connections_current 4100
telemt_connections_me_current 4100
telemt_handshake_timeouts_total 57192
telemt_upstream_connect_attempt_total 21397
telemt_upstream_connect_success_total 21305
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 21367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10660
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10620
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 855
telemt_me_reconnect_success_total 481
telemt_me_reader_eof_total 446
telemt_me_idle_close_by_peer_total 446
telemt_me_route_drop_no_conn_total 609087
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1857154
telemt_me_endpoint_quarantine_total 397
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 393
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
telemt_desync_total 7277
telemt_desync_full_logged_total 2432
telemt_desync_suppressed_total 4845
telemt_desync_frames_bucket_total{bucket="1_2"} 1760
telemt_desync_frames_bucket_total{bucket="3_10"} 2732
telemt_desync_frames_bucket_total{bucket="gt_10"} 2785
telemt_pool_swap_total 55
telemt_pool_force_close_total 1374
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 137
telemt_me_draining_writers_reap_progress_total 19240
telemt_me_writer_removed_unexpected_total 440
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1449
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18245
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1350
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17866
telemt_me_writer_teardown_success_total{mode="normal"} 19694
telemt_me_writer_teardown_noop_total 19240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38779
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38927
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 38934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 38934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 38934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 38934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 38934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 38934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 38934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 38934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 38934
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.089628
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 38934
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 137
telemt_me_refill_failed_total 19
telemt_me_writer_restored_same_endpoint_total 430
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 1851101
telemt_user_connections_current{user="hello"} 4100
telemt_user_octets_from_client{user="hello"} 40444227580 (37.67 GB)
telemt_user_octets_to_client{user="hello"} 870278072096 (810.51 GB)
telemt_user_unique_ips_current{user="hello"} 1478
telemt_user_unique_ips_recent_window{user="hello"} 601
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 50167.5 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2173946
telemt_connections_bad_total 175270
telemt_connections_current 3560
telemt_connections_me_current 3560
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 53590
telemt_upstream_connect_attempt_total 37592
telemt_upstream_connect_success_total 37371
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 37549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12288
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 514
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 579
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_reconnect_attempts_total 3073
telemt_me_reconnect_success_total 623
telemt_me_reader_eof_total 550
telemt_me_idle_close_by_peer_total 550
telemt_me_seq_mismatch_total 25
telemt_me_route_drop_no_conn_total 606939
telemt_me_route_drop_channel_closed_total 38
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1749505
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 392
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
telemt_desync_total 6653
telemt_desync_full_logged_total 2258
telemt_desync_suppressed_total 4395
telemt_desync_frames_bucket_total{bucket="1_2"} 1776
telemt_desync_frames_bucket_total{bucket="3_10"} 2476
telemt_desync_frames_bucket_total{bucket="gt_10"} 2401
telemt_pool_swap_total 54
telemt_pool_force_close_total 1319
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 18448
telemt_me_writer_removed_unexpected_total 559
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1700
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17334
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1238
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 81
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17129
telemt_me_writer_teardown_success_total{mode="normal"} 19034
telemt_me_writer_teardown_noop_total 18449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37026
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37408
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37483
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.519620
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37483
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 139
telemt_me_writer_restored_same_endpoint_total 482
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 45
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 1760722
telemt_user_connections_current{user="hello"} 3560
telemt_user_octets_from_client{user="hello"} 30470511821 (28.38 GB)
telemt_user_octets_to_client{user="hello"} 780733171504 (727.11 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1346
telemt_user_unique_ips_recent_window{user="hello"} 511
```