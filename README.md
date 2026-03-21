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

# Server Metrics 2026-03-21 15:58:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 69776.3 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2489353
telemt_connections_bad_total 148218
telemt_connections_current 1365
telemt_connections_me_current 1365
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 78713
telemt_upstream_connect_attempt_total 29625
telemt_upstream_connect_success_total 29494
telemt_upstream_connect_fail_total 88
telemt_upstream_connect_attempts_per_request{bucket="1"} 29582
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17169
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 88
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 98
telemt_me_reconnect_attempts_total 1717
telemt_me_reconnect_success_total 676
telemt_me_reader_eof_total 649
telemt_me_idle_close_by_peer_total 649
telemt_me_route_drop_no_conn_total 2127106
telemt_me_route_drop_channel_closed_total 653
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1981789
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 488
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 544
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
telemt_desync_total 7871
telemt_desync_full_logged_total 2714
telemt_desync_suppressed_total 5157
telemt_desync_frames_bucket_total{bucket="1_2"} 1725
telemt_desync_frames_bucket_total{bucket="3_10"} 2987
telemt_desync_frames_bucket_total{bucket="gt_10"} 3159
telemt_pool_swap_total 75
telemt_pool_force_close_total 2271
telemt_pool_stale_pick_total 28
telemt_me_writer_close_signal_drop_total 510
telemt_me_draining_writers_reap_progress_total 23771
telemt_me_writer_removed_unexpected_total 627
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2045
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22137
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2152
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 119
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21500
telemt_me_writer_teardown_success_total{mode="normal"} 24182
telemt_me_writer_teardown_noop_total 23777
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39878
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 42731
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46836
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47931
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47959
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 222.889912
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47959
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 510
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 578
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 1983194
telemt_user_connections_current{user="hello"} 1365
telemt_user_octets_from_client{user="hello"} 27986697077 (26.06 GB)
telemt_user_octets_to_client{user="hello"} 490750290130 (457.05 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 528
telemt_user_unique_ips_recent_window{user="hello"} 213
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 901.5 (0h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29584
telemt_connections_bad_total 1537
telemt_connections_current 1085
telemt_connections_me_current 1085
telemt_handshake_timeouts_total 716
telemt_upstream_connect_attempt_total 382
telemt_upstream_connect_success_total 382
telemt_upstream_connect_attempts_per_request{bucket="1"} 382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 178
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 202
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 2
telemt_me_reconnect_success_total 1
telemt_me_reader_eof_total 1
telemt_me_idle_close_by_peer_total 1
telemt_me_route_drop_no_conn_total 12522
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 25093
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 8
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
telemt_desync_total 108
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 49
telemt_desync_frames_bucket_total{bucket="1_2"} 21
telemt_desync_frames_bucket_total{bucket="3_10"} 41
telemt_desync_frames_bucket_total{bucket="gt_10"} 46
telemt_me_draining_writers_reap_progress_total 274
telemt_me_writer_removed_unexpected_total 1
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 268
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 274
telemt_me_writer_teardown_success_total{mode="normal"} 275
telemt_me_writer_teardown_noop_total 274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 549
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.012382
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 549
telemt_me_writer_restored_same_endpoint_total 1
telemt_user_connections_total{user="hello"} 25093
telemt_user_connections_current{user="hello"} 1085
telemt_user_octets_from_client{user="hello"} 195929356 (186.85 MB)
telemt_user_octets_to_client{user="hello"} 6953270668 (6.48 GB)
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 403
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 69773.8 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5038179
telemt_connections_bad_total 446041
telemt_connections_current 5072
telemt_connections_me_current 5072
telemt_handshake_timeouts_total 175783
telemt_upstream_connect_attempt_total 25782
telemt_upstream_connect_success_total 25727
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 25733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11567
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14053
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1163
telemt_me_reconnect_success_total 588
telemt_me_reader_eof_total 592
telemt_me_idle_close_by_peer_total 592
telemt_me_route_drop_no_conn_total 2911591
telemt_me_route_drop_channel_closed_total 46
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4124402
telemt_me_endpoint_quarantine_total 439
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 528
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
telemt_desync_total 16951
telemt_desync_full_logged_total 5703
telemt_desync_suppressed_total 11248
telemt_desync_frames_bucket_total{bucket="1_2"} 3596
telemt_desync_frames_bucket_total{bucket="3_10"} 6714
telemt_desync_frames_bucket_total{bucket="gt_10"} 6641
telemt_pool_swap_total 74
telemt_pool_force_close_total 2431
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 381
telemt_me_draining_writers_reap_progress_total 23414
telemt_me_writer_removed_unexpected_total 572
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2055
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21674
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 34
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2232
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20983
telemt_me_writer_teardown_success_total{mode="normal"} 23729
telemt_me_writer_teardown_noop_total 23448
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 46140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 46694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 47023
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 47175
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 47177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 47177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 47177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 47177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 47177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 47177
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 90.739787
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 47177
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 381
telemt_me_refill_failed_total 30
telemt_me_writer_restored_same_endpoint_total 529
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 4119452
telemt_user_connections_current{user="hello"} 5072
telemt_user_octets_from_client{user="hello"} 65981404320 (61.45 GB)
telemt_user_octets_to_client{user="hello"} 1341627820308 (1.22 TB)
telemt_user_unique_ips_current{user="hello"} 1970
telemt_user_unique_ips_recent_window{user="hello"} 588
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 69775.1 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4069853
telemt_connections_bad_total 430074
telemt_connections_current 3767
telemt_connections_me_current 3767
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 142570
telemt_upstream_connect_attempt_total 30154
telemt_upstream_connect_success_total 29867
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 30007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15312
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 495
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 1390
telemt_me_reconnect_success_total 610
telemt_me_reader_eof_total 573
telemt_me_idle_close_by_peer_total 573
telemt_me_route_drop_no_conn_total 1297857
telemt_me_route_drop_channel_closed_total 107
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2993753
telemt_me_endpoint_quarantine_total 447
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 534
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
telemt_desync_total 14087
telemt_desync_full_logged_total 4682
telemt_desync_suppressed_total 9405
telemt_desync_frames_bucket_total{bucket="1_2"} 3544
telemt_desync_frames_bucket_total{bucket="3_10"} 5454
telemt_desync_frames_bucket_total{bucket="gt_10"} 5089
telemt_pool_swap_total 76
telemt_pool_force_close_total 2219
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 225
telemt_me_draining_writers_reap_progress_total 22546
telemt_me_writer_removed_unexpected_total 555
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1944
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21148
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2061
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 158
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20327
telemt_me_writer_teardown_success_total{mode="normal"} 23092
telemt_me_writer_teardown_noop_total 22548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44726
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45548
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45640
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45640
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 24.098264
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45640
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 225
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 514
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 2993263
telemt_user_connections_current{user="hello"} 3767
telemt_user_octets_from_client{user="hello"} 65033150301 (60.57 GB)
telemt_user_octets_to_client{user="hello"} 1384896247387 (1.26 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1508
telemt_user_unique_ips_recent_window{user="hello"} 506
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 69739.8 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4008156
telemt_connections_bad_total 411103
telemt_connections_current 3600
telemt_connections_me_current 3600
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 121421
telemt_upstream_connect_attempt_total 35414
telemt_upstream_connect_success_total 35175
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 35308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15359
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 295
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 864
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 55
telemt_me_reconnect_attempts_total 1454
telemt_me_reconnect_success_total 662
telemt_me_reader_eof_total 604
telemt_me_idle_close_by_peer_total 604
telemt_me_route_drop_no_conn_total 1387823
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2975822
telemt_me_endpoint_quarantine_total 494
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 525
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
telemt_me_writers_active_current 44
telemt_desync_total 13727
telemt_desync_full_logged_total 4551
telemt_desync_suppressed_total 9176
telemt_desync_frames_bucket_total{bucket="1_2"} 3419
telemt_desync_frames_bucket_total{bucket="3_10"} 5163
telemt_desync_frames_bucket_total{bucket="gt_10"} 5145
telemt_pool_swap_total 74
telemt_pool_force_close_total 2131
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 245
telemt_me_draining_writers_reap_progress_total 23975
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2030
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22557
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1947
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 184
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21844
telemt_me_writer_teardown_success_total{mode="normal"} 24587
telemt_me_writer_teardown_noop_total 23981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48568
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.808529
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48568
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 245
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 569
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 2979451
telemt_user_connections_current{user="hello"} 3600
telemt_user_octets_from_client{user="hello"} 67639048817 (62.99 GB)
telemt_user_octets_to_client{user="hello"} 1376087324240 (1.25 TB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1451
telemt_user_unique_ips_recent_window{user="hello"} 519
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 69778.2 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13787059
telemt_connections_bad_total 891923
telemt_connections_current 5392
telemt_connections_me_current 5392
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 412355
telemt_upstream_connect_attempt_total 116570
telemt_upstream_connect_success_total 106652
telemt_upstream_connect_fail_total 8855
telemt_upstream_connect_attempts_per_request{bucket="1"} 115507
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 74600
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25891
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8855
telemt_me_keepalive_timeout_total 128
telemt_me_reconnect_attempts_total 3894
telemt_me_reconnect_success_total 1420
telemt_me_reader_eof_total 991
telemt_me_idle_close_by_peer_total 990
telemt_me_route_drop_no_conn_total 27127038
telemt_me_route_drop_channel_closed_total 90
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11354363
telemt_me_endpoint_quarantine_total 536
telemt_me_single_endpoint_outage_enter_total 78
telemt_me_single_endpoint_outage_exit_total 78
telemt_me_single_endpoint_outage_reconnect_attempt_total 174
telemt_me_single_endpoint_outage_reconnect_success_total 38
telemt_me_single_endpoint_quarantine_bypass_total 174
telemt_me_single_endpoint_shadow_rotate_total 545
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
telemt_me_writers_active_current 45
telemt_desync_total 20013
telemt_desync_full_logged_total 6263
telemt_desync_suppressed_total 13750
telemt_desync_frames_bucket_total{bucket="1_2"} 4353
telemt_desync_frames_bucket_total{bucket="3_10"} 8817
telemt_desync_frames_bucket_total{bucket="gt_10"} 6843
telemt_pool_swap_total 71
telemt_pool_force_close_total 2325
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 504
telemt_me_draining_writers_reap_progress_total 22289
telemt_me_writer_removed_unexpected_total 1352
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2920
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20498
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1953
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 372
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19964
telemt_me_writer_teardown_success_total{mode="normal"} 23418
telemt_me_writer_teardown_noop_total 22301
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42817
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45441
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45700
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45710
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45719
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 174.298352
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45719
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 504
telemt_me_refill_failed_total 88
telemt_me_writer_restored_same_endpoint_total 994
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 130
telemt_me_writer_removed_unexpected_minus_restored_total 348
telemt_user_connections_total{user="hello"} 11429046
telemt_user_connections_current{user="hello"} 5392
telemt_user_octets_from_client{user="hello"} 79804759305 (74.32 GB)
telemt_user_octets_to_client{user="hello"} 820536181637 (764.18 GB)
telemt_user_msgs_from_client{user="hello"} 231133
telemt_user_msgs_to_client{user="hello"} 542131
telemt_user_unique_ips_current{user="hello"} 2026
telemt_user_unique_ips_recent_window{user="hello"} 1069
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 69745.9 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3995571
telemt_connections_bad_total 433933
telemt_connections_current 4158
telemt_connections_me_current 4158
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 85866
telemt_upstream_connect_attempt_total 29252
telemt_upstream_connect_success_total 28934
telemt_upstream_connect_fail_total 273
telemt_upstream_connect_attempts_per_request{bucket="1"} 29207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13734
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15122
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 273
telemt_me_reconnect_attempts_total 2775
telemt_me_reconnect_success_total 1035
telemt_me_reader_eof_total 1038
telemt_me_idle_close_by_peer_total 1038
telemt_me_route_drop_no_conn_total 1701158
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 34
telemt_me_route_drop_queue_full_profile_total{profile="high"} 34
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3093159
telemt_me_endpoint_quarantine_total 427
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 521
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
telemt_me_writers_active_current 46
telemt_desync_total 14945
telemt_desync_full_logged_total 5182
telemt_desync_suppressed_total 9763
telemt_desync_frames_bucket_total{bucket="1_2"} 2929
telemt_desync_frames_bucket_total{bucket="3_10"} 5932
telemt_desync_frames_bucket_total{bucket="gt_10"} 6084
telemt_pool_swap_total 69
telemt_pool_force_close_total 2034
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 206
telemt_me_draining_writers_reap_progress_total 24571
telemt_me_writer_removed_unexpected_total 1005
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2464
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23148
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1748
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 286
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22537
telemt_me_writer_teardown_success_total{mode="normal"} 25612
telemt_me_writer_teardown_noop_total 24572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49943
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50165
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50184
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.321099
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50184
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 206
telemt_me_refill_failed_total 95
telemt_me_writer_restored_same_endpoint_total 896
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 3076490
telemt_user_connections_current{user="hello"} 4158
telemt_user_octets_from_client{user="hello"} 80490496612 (74.96 GB)
telemt_user_octets_to_client{user="hello"} 1271180790402 (1.16 TB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1678
telemt_user_unique_ips_recent_window{user="hello"} 547
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 6581.5 (1h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1025416
telemt_connections_bad_total 36923
telemt_connections_current 3236
telemt_connections_me_current 3236
telemt_handshake_timeouts_total 478724
telemt_upstream_connect_attempt_total 2358
telemt_upstream_connect_success_total 2315
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 2352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1056
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 298
telemt_me_reconnect_success_total 96
telemt_me_reader_eof_total 86
telemt_me_idle_close_by_peer_total 86
telemt_me_route_drop_no_conn_total 413662
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 468304
telemt_me_endpoint_quarantine_total 27
telemt_me_single_endpoint_outage_enter_total 1
telemt_me_single_endpoint_outage_exit_total 1
telemt_me_single_endpoint_outage_reconnect_attempt_total 1
telemt_me_single_endpoint_outage_reconnect_success_total 1
telemt_me_single_endpoint_quarantine_bypass_total 1
telemt_me_single_endpoint_shadow_rotate_total 52
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
telemt_me_writers_active_current 44
telemt_desync_total 2346
telemt_desync_full_logged_total 768
telemt_desync_suppressed_total 1578
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 871
telemt_desync_frames_bucket_total{bucket="gt_10"} 1049
telemt_pool_swap_total 6
telemt_pool_force_close_total 200
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 17
telemt_me_draining_writers_reap_progress_total 1982
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 192
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 1877
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 159
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 1782
telemt_me_writer_teardown_success_total{mode="normal"} 2069
telemt_me_writer_teardown_noop_total 1982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 3949
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 3988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 4016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 4051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 4051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 4051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 4051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 4051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 4051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 4051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 4051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 4051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 4051
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.818400
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 4051
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 17
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 81
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 467589
telemt_user_connections_current{user="hello"} 3236
telemt_user_octets_from_client{user="hello"} 12300665392 (11.46 GB)
telemt_user_octets_to_client{user="hello"} 174612548932 (162.62 GB)
telemt_user_unique_ips_current{user="hello"} 1259
telemt_user_unique_ips_recent_window{user="hello"} 563
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 67731.8 (18h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1276372
telemt_connections_bad_total 142560
telemt_connections_current 718
telemt_connections_me_current 718
telemt_handshake_timeouts_total 456760
telemt_upstream_connect_attempt_total 31567
telemt_upstream_connect_success_total 31559
telemt_upstream_connect_attempts_per_request{bucket="1"} 31559
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18540
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1358
telemt_me_reconnect_success_total 567
telemt_me_reader_eof_total 566
telemt_me_idle_close_by_peer_total 566
telemt_me_route_drop_no_conn_total 279610
telemt_me_route_drop_channel_closed_total 24
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 600600
telemt_me_endpoint_quarantine_total 604
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 566
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 10
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
telemt_desync_total 3623
telemt_desync_full_logged_total 1315
telemt_desync_suppressed_total 2308
telemt_desync_frames_bucket_total{bucket="1_2"} 667
telemt_desync_frames_bucket_total{bucket="3_10"} 1304
telemt_desync_frames_bucket_total{bucket="gt_10"} 1652
telemt_pool_swap_total 74
telemt_pool_force_close_total 1739
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 28285
telemt_me_writer_removed_unexpected_total 535
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2149
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26688
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1710
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26546
telemt_me_writer_teardown_success_total{mode="normal"} 28837
telemt_me_writer_teardown_noop_total 28285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 56888
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57122
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.569647
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57122
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 472
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 600199
telemt_user_connections_current{user="hello"} 718
telemt_user_octets_from_client{user="hello"} 12406001867 (11.55 GB)
telemt_user_octets_to_client{user="hello"} 231270339729 (215.39 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 270
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 69750.3 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4449385
telemt_connections_bad_total 412119
telemt_connections_current 4756
telemt_connections_me_current 4756
telemt_handshake_timeouts_total 144910
telemt_upstream_connect_attempt_total 27604
telemt_upstream_connect_success_total 27491
telemt_upstream_connect_fail_total 78
telemt_upstream_connect_attempts_per_request{bucket="1"} 27569
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13604
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13850
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 78
telemt_me_reconnect_attempts_total 1190
telemt_me_reconnect_success_total 619
telemt_me_reader_eof_total 586
telemt_me_idle_close_by_peer_total 586
telemt_me_route_drop_no_conn_total 1347092
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3518713
telemt_me_endpoint_quarantine_total 502
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 533
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
telemt_me_writers_active_current 44
telemt_desync_total 13733
telemt_desync_full_logged_total 4540
telemt_desync_suppressed_total 9193
telemt_desync_frames_bucket_total{bucket="1_2"} 3239
telemt_desync_frames_bucket_total{bucket="3_10"} 5114
telemt_desync_frames_bucket_total{bucket="gt_10"} 5380
telemt_pool_swap_total 77
telemt_pool_force_close_total 2032
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 230
telemt_me_draining_writers_reap_progress_total 24760
telemt_me_writer_removed_unexpected_total 574
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1982
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23354
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1984
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 48
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22728
telemt_me_writer_teardown_success_total{mode="normal"} 25336
telemt_me_writer_teardown_noop_total 24760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49923
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 50052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 50096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50096
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.089882
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50096
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 230
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 548
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 3510146
telemt_user_connections_current{user="hello"} 4756
telemt_user_octets_from_client{user="hello"} 70669580420 (65.82 GB)
telemt_user_octets_to_client{user="hello"} 1646296760780 (1.50 TB)
telemt_user_unique_ips_current{user="hello"} 1705
telemt_user_unique_ips_recent_window{user="hello"} 612
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 69746.9 (19h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3944598
telemt_connections_bad_total 359460
telemt_connections_current 3733
telemt_connections_me_current 3733
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 121675
telemt_upstream_connect_attempt_total 44100
telemt_upstream_connect_success_total 43789
telemt_upstream_connect_fail_total 256
telemt_upstream_connect_attempts_per_request{bucket="1"} 44045
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15702
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 602
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 256
telemt_me_reconnect_attempts_total 3946
telemt_me_reconnect_success_total 886
telemt_me_reader_eof_total 764
telemt_me_idle_close_by_peer_total 764
telemt_me_seq_mismatch_total 33
telemt_me_route_drop_no_conn_total 1427036
telemt_me_route_drop_channel_closed_total 107
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3144024
telemt_me_endpoint_quarantine_total 583
telemt_me_single_endpoint_outage_enter_total 21
telemt_me_single_endpoint_outage_exit_total 21
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 21
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 529
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
telemt_desync_total 12246
telemt_desync_full_logged_total 4153
telemt_desync_suppressed_total 8093
telemt_desync_frames_bucket_total{bucket="1_2"} 3058
telemt_desync_frames_bucket_total{bucket="3_10"} 4553
telemt_desync_frames_bucket_total{bucket="gt_10"} 4635
telemt_pool_swap_total 75
telemt_pool_force_close_total 1971
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 218
telemt_me_draining_writers_reap_progress_total 24153
telemt_me_writer_removed_unexpected_total 777
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2373
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22590
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1805
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 166
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22182
telemt_me_writer_teardown_success_total{mode="normal"} 24963
telemt_me_writer_teardown_noop_total 24154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 48201
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48783
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49117
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.234889
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49117
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 218
telemt_me_refill_failed_total 174
telemt_me_writer_restored_same_endpoint_total 682
telemt_me_writer_restored_fallback_total 43
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 3152276
telemt_user_connections_current{user="hello"} 3733
telemt_user_octets_from_client{user="hello"} 57158681489 (53.23 GB)
telemt_user_octets_to_client{user="hello"} 1345600457908 (1.22 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1432
telemt_user_unique_ips_recent_window{user="hello"} 551
```