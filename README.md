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

# Server Metrics 2026-03-22 15:48:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 67346.3 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2359893
telemt_connections_bad_total 126770
telemt_connections_current 1706
telemt_connections_me_current 1706
telemt_handshake_timeouts_total 86309
telemt_upstream_connect_attempt_total 24909
telemt_upstream_connect_success_total 24908
telemt_upstream_connect_attempts_per_request{bucket="1"} 24908
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8665
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16176
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1019
telemt_me_reconnect_success_total 427
telemt_me_reader_eof_total 429
telemt_me_idle_close_by_peer_total 429
telemt_me_route_drop_no_conn_total 1907670
telemt_me_route_drop_channel_closed_total 767
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2005482
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 527
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
telemt_desync_total 9860
telemt_desync_full_logged_total 3056
telemt_desync_suppressed_total 6804
telemt_desync_frames_bucket_total{bucket="1_2"} 2652
telemt_desync_frames_bucket_total{bucket="3_10"} 3692
telemt_desync_frames_bucket_total{bucket="gt_10"} 3516
telemt_pool_swap_total 74
telemt_pool_force_close_total 2276
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 428
telemt_me_draining_writers_reap_progress_total 22738
telemt_me_writer_removed_unexpected_total 416
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1651
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21302
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2229
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20462
telemt_me_writer_teardown_success_total{mode="normal"} 22953
telemt_me_writer_teardown_noop_total 22744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38952
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 42983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45481
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45697
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 203.573940
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45697
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 428
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 2002152
telemt_user_connections_current{user="hello"} 1706
telemt_user_octets_from_client{user="hello"} 30443048744 (28.35 GB)
telemt_user_octets_to_client{user="hello"} 536708882924 (499.85 GB)
telemt_user_unique_ips_current{user="hello"} 646
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 80712.6 (22h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3551545
telemt_connections_bad_total 323316
telemt_connections_current 1565
telemt_connections_me_current 1565
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 85646
telemt_upstream_connect_attempt_total 51056
telemt_upstream_connect_success_total 50432
telemt_upstream_connect_fail_total 552
telemt_upstream_connect_attempts_per_request{bucket="1"} 50984
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20766
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 552
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5998
telemt_me_reconnect_success_total 2169
telemt_me_reader_eof_total 2107
telemt_me_idle_close_by_peer_total 2107
telemt_me_route_drop_no_conn_total 3517911
telemt_me_route_drop_channel_closed_total 35
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2814093
telemt_me_endpoint_quarantine_total 644
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 624
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
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
telemt_desync_total 10902
telemt_desync_full_logged_total 6063
telemt_desync_suppressed_total 4839
telemt_desync_frames_bucket_total{bucket="1_2"} 2553
telemt_desync_frames_bucket_total{bucket="3_10"} 4293
telemt_desync_frames_bucket_total{bucket="gt_10"} 4056
telemt_pool_swap_total 75
telemt_pool_force_close_total 2228
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 187
telemt_me_draining_writers_reap_progress_total 32006
telemt_me_writer_removed_unexpected_total 2063
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3891
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30183
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29778
telemt_me_writer_teardown_success_total{mode="normal"} 34074
telemt_me_writer_teardown_noop_total 32006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 65780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66080
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66080
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.594119
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66080
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 187
telemt_me_refill_failed_total 149
telemt_me_writer_restored_same_endpoint_total 1879
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 160
telemt_user_connections_total{user="hello"} 2825433
telemt_user_connections_current{user="hello"} 1565
telemt_user_octets_from_client{user="hello"} 34585541063 (32.21 GB)
telemt_user_octets_to_client{user="hello"} 620406978902 (577.80 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 879
telemt_user_unique_ips_recent_window{user="hello"} 411
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 155572.6 (43h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15189782
telemt_connections_bad_total 1393294
telemt_connections_current 2256
telemt_connections_me_current 2256
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 369743
telemt_upstream_connect_attempt_total 70485
telemt_upstream_connect_success_total 70390
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 70407
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35484
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33228
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1671
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2588
telemt_me_reconnect_success_total 1336
telemt_me_reader_eof_total 1274
telemt_me_idle_close_by_peer_total 1272
telemt_me_route_drop_no_conn_total 13772587
telemt_me_route_drop_channel_closed_total 137
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12156285
telemt_me_endpoint_quarantine_total 981
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1158
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 49302
telemt_desync_full_logged_total 15465
telemt_desync_suppressed_total 33837
telemt_desync_frames_bucket_total{bucket="1_2"} 11071
telemt_desync_frames_bucket_total{bucket="3_10"} 19280
telemt_desync_frames_bucket_total{bucket="gt_10"} 18951
telemt_pool_swap_total 167
telemt_pool_force_close_total 5691
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 930
telemt_me_draining_writers_reap_progress_total 51165
telemt_me_writer_removed_unexpected_total 1229
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4448
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47252
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5231
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 460
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45474
telemt_me_writer_teardown_success_total{mode="normal"} 51700
telemt_me_writer_teardown_noop_total 51215
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 97745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99875
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102911
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102915
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 292.895431
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102915
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 930
telemt_me_refill_failed_total 69
telemt_me_writer_restored_same_endpoint_total 1146
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 12157578
telemt_user_connections_current{user="hello"} 2256
telemt_user_octets_from_client{user="hello"} 171024314613 (159.28 GB)
telemt_user_octets_to_client{user="hello"} 3129935177815 (2.85 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 916
telemt_user_unique_ips_recent_window{user="hello"} 388
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 155573.8 (43h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10964660
telemt_connections_bad_total 1061711
telemt_connections_current 1501
telemt_connections_me_current 1501
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 324649
telemt_upstream_connect_attempt_total 82660
telemt_upstream_connect_success_total 81508
telemt_upstream_connect_fail_total 828
telemt_upstream_connect_attempts_per_request{bucket="1"} 82336
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44557
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33102
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 828
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3899
telemt_me_reconnect_success_total 1582
telemt_me_reader_eof_total 1449
telemt_me_idle_close_by_peer_total 1449
telemt_me_route_drop_no_conn_total 4338707
telemt_me_route_drop_channel_closed_total 477
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8180515
telemt_me_endpoint_quarantine_total 977
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 32
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 32
telemt_me_single_endpoint_shadow_rotate_total 1177
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
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
telemt_desync_total 36315
telemt_desync_full_logged_total 12197
telemt_desync_suppressed_total 24118
telemt_desync_frames_bucket_total{bucket="1_2"} 8905
telemt_desync_frames_bucket_total{bucket="3_10"} 13981
telemt_desync_frames_bucket_total{bucket="gt_10"} 13429
telemt_pool_swap_total 165
telemt_pool_force_close_total 5126
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 664
telemt_me_draining_writers_reap_progress_total 49457
telemt_me_writer_removed_unexpected_total 1481
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4560
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46235
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4652
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44331
telemt_me_writer_teardown_success_total{mode="normal"} 50795
telemt_me_writer_teardown_noop_total 49475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 94040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 96971
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98046
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99140
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100260
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100270
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 99.180762
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100270
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 664
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1344
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 123
telemt_user_connections_total{user="hello"} 8119307
telemt_user_connections_current{user="hello"} 1501
telemt_user_octets_from_client{user="hello"} 203572521061 (189.59 GB)
telemt_user_octets_to_client{user="hello"} 3661139766170 (3.33 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 592
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 155538.1 (43h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10382970
telemt_connections_bad_total 892275
telemt_connections_current 1203
telemt_connections_me_current 1203
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 331074
telemt_upstream_connect_attempt_total 67882
telemt_upstream_connect_success_total 66952
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 67134
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31627
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1259
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2059
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4622
telemt_me_reconnect_success_total 1864
telemt_me_reader_eof_total 1621
telemt_me_idle_close_by_peer_total 1620
telemt_me_route_drop_no_conn_total 5108831
telemt_me_route_drop_channel_closed_total 356
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7838778
telemt_me_endpoint_quarantine_total 1065
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1143
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
telemt_me_writers_active_current 44
telemt_desync_total 35899
telemt_desync_full_logged_total 11888
telemt_desync_suppressed_total 24011
telemt_desync_frames_bucket_total{bucket="1_2"} 9080
telemt_desync_frames_bucket_total{bucket="3_10"} 13723
telemt_desync_frames_bucket_total{bucket="gt_10"} 13096
telemt_pool_swap_total 162
telemt_pool_force_close_total 5075
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 49898
telemt_me_writer_removed_unexpected_total 1761
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4993
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46578
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4538
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 537
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44823
telemt_me_writer_teardown_success_total{mode="normal"} 51571
telemt_me_writer_teardown_noop_total 49969
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 96109
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98593
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 99489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101276
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101432
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101486
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101540
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3170.151595
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101540
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1615
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 138
telemt_user_connections_total{user="hello"} 7831837
telemt_user_connections_current{user="hello"} 1203
telemt_user_octets_from_client{user="hello"} 180813341969 (168.40 GB)
telemt_user_octets_to_client{user="hello"} 3254511523173 (2.96 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 494
telemt_user_unique_ips_recent_window{user="hello"} 167
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 25818.0 (7h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10019791
telemt_connections_bad_total 612419
telemt_connections_current 2237
telemt_connections_me_current 2237
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 174450
telemt_upstream_connect_attempt_total 34918
telemt_upstream_connect_success_total 33166
telemt_upstream_connect_fail_total 1247
telemt_upstream_connect_attempts_per_request{bucket="1"} 34413
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18042
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1247
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5791
telemt_me_reconnect_success_total 681
telemt_me_reader_eof_total 426
telemt_me_idle_close_by_peer_total 426
telemt_me_route_drop_no_conn_total 24858851
telemt_me_route_drop_channel_closed_total 43
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8348698
telemt_me_endpoint_quarantine_total 164
telemt_me_single_endpoint_outage_enter_total 48
telemt_me_single_endpoint_outage_exit_total 48
telemt_me_single_endpoint_outage_reconnect_attempt_total 82
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 82
telemt_me_single_endpoint_shadow_rotate_total 202
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
telemt_desync_total 12775
telemt_desync_full_logged_total 3266
telemt_desync_suppressed_total 9509
telemt_desync_frames_bucket_total{bucket="1_2"} 2218
telemt_desync_frames_bucket_total{bucket="3_10"} 5202
telemt_desync_frames_bucket_total{bucket="gt_10"} 5355
telemt_pool_swap_total 24
telemt_pool_force_close_total 982
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 358
telemt_me_draining_writers_reap_progress_total 6963
telemt_me_writer_removed_unexpected_total 588
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1190
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6325
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 708
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5981
telemt_me_writer_teardown_success_total{mode="normal"} 7515
telemt_me_writer_teardown_noop_total 6968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11835
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 13130
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 13582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14483
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14483
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 34.996163
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14483
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 358
telemt_me_refill_failed_total 290
telemt_me_writer_restored_same_endpoint_total 464
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 8366965
telemt_user_connections_current{user="hello"} 2237
telemt_user_octets_from_client{user="hello"} 57002029030 (53.09 GB)
telemt_user_octets_to_client{user="hello"} 271258915292 (252.63 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 808
telemt_user_unique_ips_recent_window{user="hello"} 316
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 155544.6 (43h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10145355
telemt_connections_bad_total 845321
telemt_connections_current 1889
telemt_connections_me_current 1889
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 223736
telemt_upstream_connect_attempt_total 96599
telemt_upstream_connect_success_total 95620
telemt_upstream_connect_fail_total 833
telemt_upstream_connect_attempts_per_request{bucket="1"} 96453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59251
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34832
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1299
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 833
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71697
telemt_me_reconnect_success_total 2586
telemt_me_reader_eof_total 2290
telemt_me_idle_close_by_peer_total 2289
telemt_me_route_drop_no_conn_total 5036116
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8005515
telemt_me_endpoint_quarantine_total 1050
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1159
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
telemt_me_writers_active_current 46
telemt_desync_total 41621
telemt_desync_full_logged_total 14206
telemt_desync_suppressed_total 27415
telemt_desync_frames_bucket_total{bucket="1_2"} 8476
telemt_desync_frames_bucket_total{bucket="3_10"} 16116
telemt_desync_frames_bucket_total{bucket="gt_10"} 17029
telemt_pool_swap_total 158
telemt_pool_force_close_total 4707
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 591
telemt_me_draining_writers_reap_progress_total 52962
telemt_me_writer_removed_unexpected_total 2334
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5670
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49646
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4025
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 682
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48255
telemt_me_writer_teardown_success_total{mode="normal"} 55316
telemt_me_writer_teardown_noop_total 52963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 108235
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 108269
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 108272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 108272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 108275
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 108279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 108279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 108279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 108279
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 108279
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.352200
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 108279
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 591
telemt_me_refill_failed_total 4262
telemt_me_writer_restored_same_endpoint_total 2174
telemt_me_writer_restored_fallback_total 44
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7360
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 8009555
telemt_user_connections_current{user="hello"} 1889
telemt_user_octets_from_client{user="hello"} 181356972509 (168.90 GB)
telemt_user_octets_to_client{user="hello"} 3012016196724 (2.74 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 696
telemt_user_unique_ips_recent_window{user="hello"} 226
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 92380.7 (25h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10549289
telemt_connections_bad_total 389473
telemt_connections_current 1419
telemt_connections_me_current 1419
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4451526
telemt_upstream_connect_attempt_total 44622
telemt_upstream_connect_success_total 44295
telemt_upstream_connect_fail_total 317
telemt_upstream_connect_attempts_per_request{bucket="1"} 44612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25017
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 317
telemt_me_reconnect_attempts_total 48034
telemt_me_reconnect_success_total 1498
telemt_me_reader_eof_total 1161
telemt_me_idle_close_by_peer_total 1160
telemt_me_route_drop_no_conn_total 3893917
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5051134
telemt_me_endpoint_quarantine_total 603
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 695
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 27597
telemt_desync_full_logged_total 9317
telemt_desync_suppressed_total 18280
telemt_desync_frames_bucket_total{bucket="1_2"} 5559
telemt_desync_frames_bucket_total{bucket="3_10"} 10902
telemt_desync_frames_bucket_total{bucket="gt_10"} 11136
telemt_pool_swap_total 97
telemt_pool_force_close_total 3006
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 310
telemt_me_draining_writers_reap_progress_total 31730
telemt_me_writer_removed_unexpected_total 1224
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2861
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30123
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2587
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28724
telemt_me_writer_teardown_success_total{mode="normal"} 32984
telemt_me_writer_teardown_noop_total 31737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63629
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64721
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64721
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.663571
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64721
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 310
telemt_me_refill_failed_total 2705
telemt_me_writer_restored_same_endpoint_total 1332
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 5044768
telemt_user_connections_current{user="hello"} 1419
telemt_user_octets_from_client{user="hello"} 108834959248 (101.36 GB)
telemt_user_octets_to_client{user="hello"} 1900982395102 (1.73 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 573
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 73351.5 (20h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 958056
telemt_connections_bad_total 13406
telemt_connections_current 1084
telemt_connections_me_current 1084
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18551
telemt_upstream_connect_attempt_total 36266
telemt_upstream_connect_success_total 36175
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 36250
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16438
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_reconnect_attempts_total 1624
telemt_me_reconnect_success_total 692
telemt_me_reader_eof_total 667
telemt_me_idle_close_by_peer_total 667
telemt_me_route_drop_no_conn_total 329029
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 850518
telemt_me_endpoint_quarantine_total 637
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 608
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_desync_total 4728
telemt_desync_full_logged_total 1443
telemt_desync_suppressed_total 3285
telemt_desync_frames_bucket_total{bucket="1_2"} 1105
telemt_desync_frames_bucket_total{bucket="3_10"} 1877
telemt_desync_frames_bucket_total{bucket="gt_10"} 1746
telemt_pool_swap_total 78
telemt_pool_force_close_total 1966
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 29982
telemt_me_writer_removed_unexpected_total 644
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2316
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28335
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1888
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28016
telemt_me_writer_teardown_success_total{mode="normal"} 30651
telemt_me_writer_teardown_noop_total 29985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 59990
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 60458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 60636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 60636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 60636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 60636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 60636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 60636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 60636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 60636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 60636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 60636
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.521753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 60636
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 590
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 851554
telemt_user_connections_current{user="hello"} 1084
telemt_user_octets_from_client{user="hello"} 15419380193 (14.36 GB)
telemt_user_octets_to_client{user="hello"} 383252340391 (356.93 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 417
telemt_user_unique_ips_recent_window{user="hello"} 174
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 155549.1 (43h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12421463
telemt_connections_bad_total 1442330
telemt_connections_current 1916
telemt_connections_me_current 1916
telemt_handshake_timeouts_total 340615
telemt_upstream_connect_attempt_total 58286
telemt_upstream_connect_success_total 58059
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 58236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28637
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29355
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_reconnect_attempts_total 2262
telemt_me_reconnect_success_total 1206
telemt_me_reader_eof_total 1170
telemt_me_idle_close_by_peer_total 1170
telemt_me_route_drop_no_conn_total 4144921
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9387049
telemt_me_endpoint_quarantine_total 1051
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1161
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 38458
telemt_desync_full_logged_total 12563
telemt_desync_suppressed_total 25895
telemt_desync_frames_bucket_total{bucket="1_2"} 9136
telemt_desync_frames_bucket_total{bucket="3_10"} 14252
telemt_desync_frames_bucket_total{bucket="gt_10"} 15070
telemt_pool_swap_total 172
telemt_pool_force_close_total 4758
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 613
telemt_me_draining_writers_reap_progress_total 52514
telemt_me_writer_removed_unexpected_total 1124
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4301
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 49369
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4585
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47756
telemt_me_writer_teardown_success_total{mode="normal"} 53670
telemt_me_writer_teardown_noop_total 52516
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105404
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106186
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.945109
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106186
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 613
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1055
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9356397
telemt_user_connections_current{user="hello"} 1916
telemt_user_octets_from_client{user="hello"} 182380600432 (169.86 GB)
telemt_user_octets_to_client{user="hello"} 4134106908428 (3.76 TB)
telemt_user_unique_ips_current{user="hello"} 684
telemt_user_unique_ips_recent_window{user="hello"} 218
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 155545.8 (43h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10765210
telemt_connections_bad_total 1202404
telemt_connections_current 1609
telemt_connections_me_current 1609
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 277794
telemt_upstream_connect_attempt_total 84073
telemt_upstream_connect_success_total 83446
telemt_upstream_connect_fail_total 543
telemt_upstream_connect_attempts_per_request{bucket="1"} 83989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45929
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34580
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2028
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 543
telemt_me_reconnect_attempts_total 8874
telemt_me_reconnect_success_total 2037
telemt_me_reader_eof_total 1902
telemt_me_idle_close_by_peer_total 1902
telemt_me_seq_mismatch_total 74
telemt_me_route_drop_no_conn_total 5393629
telemt_me_route_drop_channel_closed_total 346
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8320615
telemt_me_endpoint_quarantine_total 1179
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1163
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_desync_total 38048
telemt_desync_full_logged_total 12293
telemt_desync_suppressed_total 25755
telemt_desync_frames_bucket_total{bucket="1_2"} 9462
telemt_desync_frames_bucket_total{bucket="3_10"} 14184
telemt_desync_frames_bucket_total{bucket="gt_10"} 14402
telemt_pool_swap_total 164
telemt_pool_force_close_total 4603
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 599
telemt_me_draining_writers_reap_progress_total 51956
telemt_me_writer_removed_unexpected_total 1929
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5401
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48551
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4164
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47353
telemt_me_writer_teardown_success_total{mode="normal"} 53952
telemt_me_writer_teardown_noop_total 51961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 103413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 105041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 105547
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 105863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 105913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 105913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 105913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 105913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 105913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 105913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 105913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 105913
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 105913
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.452888
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 105913
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 599
telemt_me_refill_failed_total 351
telemt_me_writer_restored_same_endpoint_total 1657
telemt_me_writer_restored_fallback_total 99
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 173
telemt_user_connections_total{user="hello"} 8326666
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 146748624841 (136.67 GB)
telemt_user_octets_to_client{user="hello"} 3177761282547 (2.89 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 598
telemt_user_unique_ips_recent_window{user="hello"} 211
```