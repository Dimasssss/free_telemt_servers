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

# Server Metrics 2026-03-23 05:05:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 115132.1 (31h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3950747
telemt_connections_bad_total 388809
telemt_connections_current 1998
telemt_connections_me_current 1998
telemt_handshake_timeouts_total 132860
telemt_upstream_connect_attempt_total 42850
telemt_upstream_connect_success_total 42849
telemt_upstream_connect_attempts_per_request{bucket="1"} 42849
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27832
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 96
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 5
telemt_me_keepalive_timeout_total 470
telemt_me_reconnect_attempts_total 1475
telemt_me_reconnect_success_total 673
telemt_me_reader_eof_total 693
telemt_me_idle_close_by_peer_total 693
telemt_me_route_drop_no_conn_total 3060495
telemt_me_route_drop_channel_closed_total 1266
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3217167
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 899
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
telemt_me_writers_active_current 45
telemt_desync_total 13776
telemt_desync_full_logged_total 4398
telemt_desync_suppressed_total 9378
telemt_desync_frames_bucket_total{bucket="1_2"} 3587
telemt_desync_frames_bucket_total{bucket="3_10"} 5092
telemt_desync_frames_bucket_total{bucket="gt_10"} 5097
telemt_pool_swap_total 127
telemt_pool_force_close_total 3881
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 705
telemt_me_draining_writers_reap_progress_total 39249
telemt_me_writer_removed_unexpected_total 667
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2805
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36726
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3816
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 65
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35368
telemt_me_writer_teardown_success_total{mode="normal"} 39531
telemt_me_writer_teardown_noop_total 39262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64534
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69283
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 76499
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78788
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78793
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 396.222058
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78793
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 705
telemt_me_refill_failed_total 42
telemt_me_writer_restored_same_endpoint_total 604
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 3205601
telemt_user_connections_current{user="hello"} 1998
telemt_user_octets_from_client{user="hello"} 44644687852 (41.58 GB)
telemt_user_octets_to_client{user="hello"} 874279070924 (814.24 GB)
telemt_user_unique_ips_current{user="hello"} 690
telemt_user_unique_ips_recent_window{user="hello"} 582
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 128498.4 (35h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4126958
telemt_connections_bad_total 383815
telemt_connections_current 563
telemt_connections_me_current 563
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 105880
telemt_upstream_connect_attempt_total 80326
telemt_upstream_connect_success_total 79367
telemt_upstream_connect_fail_total 851
telemt_upstream_connect_attempts_per_request{bucket="1"} 80218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43874
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35267
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 226
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 851
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 10818
telemt_me_reconnect_success_total 3878
telemt_me_reader_eof_total 3854
telemt_me_idle_close_by_peer_total 3854
telemt_me_route_drop_no_conn_total 3664412
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3273249
telemt_me_endpoint_quarantine_total 1048
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_single_endpoint_outage_enter_total 53
telemt_me_single_endpoint_outage_exit_total 53
telemt_me_single_endpoint_outage_reconnect_attempt_total 54
telemt_me_single_endpoint_outage_reconnect_success_total 52
telemt_me_single_endpoint_quarantine_bypass_total 54
telemt_me_single_endpoint_shadow_rotate_total 1012
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
telemt_desync_total 13474
telemt_desync_full_logged_total 7593
telemt_desync_suppressed_total 5881
telemt_desync_frames_bucket_total{bucket="1_2"} 3072
telemt_desync_frames_bucket_total{bucket="3_10"} 5289
telemt_desync_frames_bucket_total{bucket="gt_10"} 5113
telemt_pool_swap_total 121
telemt_pool_force_close_total 3368
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 260
telemt_me_draining_writers_reap_progress_total 53864
telemt_me_writer_removed_unexpected_total 3775
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6816
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50864
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2886
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 482
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50496
telemt_me_writer_teardown_success_total{mode="normal"} 57680
telemt_me_writer_teardown_noop_total 53865
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109552
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111159
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 111467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 111530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 111543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 111545
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 111545
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.832266
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 111545
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 260
telemt_me_refill_failed_total 273
telemt_me_writer_restored_same_endpoint_total 3434
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 3287697
telemt_user_connections_current{user="hello"} 563
telemt_user_octets_from_client{user="hello"} 44255634007 (41.22 GB)
telemt_user_octets_to_client{user="hello"} 825450802765 (768.76 GB)
telemt_user_msgs_from_client{user="hello"} 52128
telemt_user_msgs_to_client{user="hello"} 188269
telemt_user_unique_ips_current{user="hello"} 352
telemt_user_unique_ips_recent_window{user="hello"} 189
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 203358.4 (56h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16616136
telemt_connections_bad_total 1684897
telemt_connections_current 1412
telemt_connections_me_current 1412
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 405822
telemt_upstream_connect_attempt_total 91433
telemt_upstream_connect_success_total 91326
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 91343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45103
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1731
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 3204
telemt_me_reconnect_success_total 1676
telemt_me_reader_eof_total 1634
telemt_me_idle_close_by_peer_total 1632
telemt_me_route_drop_no_conn_total 14101967
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13196543
telemt_me_endpoint_quarantine_total 1378
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1538
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 48
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
telemt_desync_total 54966
telemt_desync_full_logged_total 17565
telemt_desync_suppressed_total 37401
telemt_desync_frames_bucket_total{bucket="1_2"} 12256
telemt_desync_frames_bucket_total{bucket="3_10"} 21523
telemt_desync_frames_bucket_total{bucket="gt_10"} 21187
telemt_pool_swap_total 220
telemt_pool_force_close_total 7070
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1096
telemt_me_draining_writers_reap_progress_total 70303
telemt_me_writer_removed_unexpected_total 1567
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5902
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 65254
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 6600
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 63233
telemt_me_writer_teardown_success_total{mode="normal"} 71156
telemt_me_writer_teardown_noop_total 70357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 130152
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 133965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 135774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 138185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 141474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 141504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 141505
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 141509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 141511
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 141513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 141513
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 318.841071
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 141513
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1096
telemt_me_refill_failed_total 84
telemt_me_writer_restored_same_endpoint_total 1454
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 13196415
telemt_user_connections_current{user="hello"} 1412
telemt_user_octets_from_client{user="hello"} 199781594725 (186.06 GB)
telemt_user_octets_to_client{user="hello"} 3577505545955 (3.25 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 627
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 203359.7 (56h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12134977
telemt_connections_bad_total 1286488
telemt_connections_current 1121
telemt_connections_me_current 1121
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 351192
telemt_upstream_connect_attempt_total 105782
telemt_upstream_connect_success_total 104370
telemt_upstream_connect_fail_total 899
telemt_upstream_connect_attempts_per_request{bucket="1"} 105269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55352
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 45010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 200
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3808
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 899
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 226
telemt_me_reconnect_attempts_total 4652
telemt_me_reconnect_success_total 2001
telemt_me_reader_eof_total 1860
telemt_me_idle_close_by_peer_total 1860
telemt_me_route_drop_no_conn_total 4602894
telemt_me_route_drop_channel_closed_total 503
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8978358
telemt_me_endpoint_quarantine_total 1388
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 1555
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
telemt_me_writers_active_current 43
telemt_desync_total 39450
telemt_desync_full_logged_total 13292
telemt_desync_suppressed_total 26158
telemt_desync_frames_bucket_total{bucket="1_2"} 9780
telemt_desync_frames_bucket_total{bucket="3_10"} 15165
telemt_desync_frames_bucket_total{bucket="gt_10"} 14505
telemt_pool_swap_total 217
telemt_pool_force_close_total 6416
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 718
telemt_me_draining_writers_reap_progress_total 68380
telemt_me_writer_removed_unexpected_total 1892
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5987
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64146
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5904
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 61964
telemt_me_writer_teardown_success_total{mode="normal"} 70133
telemt_me_writer_teardown_noop_total 68405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 131767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 135014
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 136163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 137354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 138113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 138453
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 138528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 138530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 138536
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 138538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 138538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 138538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 138538
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.612942
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 138538
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 718
telemt_me_refill_failed_total 142
telemt_me_writer_restored_same_endpoint_total 1707
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 165
telemt_user_connections_total{user="hello"} 8915951
telemt_user_connections_current{user="hello"} 1121
telemt_user_octets_from_client{user="hello"} 219538712716 (204.46 GB)
telemt_user_octets_to_client{user="hello"} 4020189598711 (3.66 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 464
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 203324.5 (56h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11283173
telemt_connections_bad_total 1032445
telemt_connections_current 931
telemt_connections_me_current 931
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 354055
telemt_upstream_connect_attempt_total 90202
telemt_upstream_connect_success_total 88628
telemt_upstream_connect_fail_total 205
telemt_upstream_connect_attempts_per_request{bucket="1"} 88833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 43596
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2067
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2369
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 205
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 1420
telemt_me_reconnect_attempts_total 5885
telemt_me_reconnect_success_total 2471
telemt_me_reader_eof_total 2217
telemt_me_idle_close_by_peer_total 2216
telemt_me_route_drop_no_conn_total 5371294
telemt_me_route_drop_channel_closed_total 384
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8487893
telemt_me_endpoint_quarantine_total 1437
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 32
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1517
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 72
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
telemt_desync_total 38594
telemt_desync_full_logged_total 12808
telemt_desync_suppressed_total 25786
telemt_desync_frames_bucket_total{bucket="1_2"} 9749
telemt_desync_frames_bucket_total{bucket="3_10"} 14779
telemt_desync_frames_bucket_total{bucket="gt_10"} 14066
telemt_pool_swap_total 213
telemt_pool_force_close_total 6302
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 761
telemt_me_draining_writers_reap_progress_total 68977
telemt_me_writer_removed_unexpected_total 2363
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6732
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 64544
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 571
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 62675
telemt_me_writer_teardown_success_total{mode="normal"} 71276
telemt_me_writer_teardown_noop_total 69048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 134472
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 137204
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 138169
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 139242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 139843
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 140057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 140185
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 140216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 140224
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 140237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 140270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 140273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 140324
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.956238
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 140324
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 761
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 2152
telemt_me_writer_restored_fallback_total 17
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 194
telemt_user_connections_total{user="hello"} 8479752
telemt_user_connections_current{user="hello"} 931
telemt_user_octets_from_client{user="hello"} 193935760627 (180.62 GB)
telemt_user_octets_to_client{user="hello"} 3519142384325 (3.20 TB)
telemt_user_msgs_from_client{user="hello"} 46587
telemt_user_msgs_to_client{user="hello"} 113900
telemt_user_unique_ips_current{user="hello"} 376
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 73618.8 (20h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11592229
telemt_connections_bad_total 683516
telemt_connections_current 1887
telemt_connections_me_current 1887
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 310369
telemt_upstream_connect_attempt_total 65480
telemt_upstream_connect_success_total 62032
telemt_upstream_connect_fail_total 2217
telemt_upstream_connect_attempts_per_request{bucket="1"} 64249
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22587
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6036
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2217
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 8293
telemt_me_reconnect_success_total 1484
telemt_me_reader_eof_total 953
telemt_me_idle_close_by_peer_total 952
telemt_me_route_drop_no_conn_total 25359094
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9601185
telemt_me_endpoint_quarantine_total 575
telemt_me_single_endpoint_outage_enter_total 103
telemt_me_single_endpoint_outage_exit_total 103
telemt_me_single_endpoint_outage_reconnect_attempt_total 201
telemt_me_single_endpoint_outage_reconnect_success_total 51
telemt_me_single_endpoint_quarantine_bypass_total 201
telemt_me_single_endpoint_shadow_rotate_total 591
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
telemt_desync_total 17164
telemt_desync_full_logged_total 4766
telemt_desync_suppressed_total 12398
telemt_desync_frames_bucket_total{bucket="1_2"} 3320
telemt_desync_frames_bucket_total{bucket="3_10"} 7016
telemt_desync_frames_bucket_total{bucket="gt_10"} 6828
telemt_pool_swap_total 76
telemt_pool_force_close_total 2368
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 523
telemt_me_draining_writers_reap_progress_total 24392
telemt_me_writer_removed_unexpected_total 1346
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3112
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22578
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2042
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 326
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22024
telemt_me_writer_teardown_success_total{mode="normal"} 25690
telemt_me_writer_teardown_noop_total 24411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 50045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 50101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 50101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 50101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 50101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 50101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 50101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 50101
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 54.809225
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 50101
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 523
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 958
telemt_me_writer_restored_fallback_total 18
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3153
telemt_me_writer_removed_unexpected_minus_restored_total 370
telemt_user_connections_total{user="hello"} 9627540
telemt_user_connections_current{user="hello"} 1887
telemt_user_octets_from_client{user="hello"} 90333393722 (84.13 GB)
telemt_user_octets_to_client{user="hello"} 706729860221 (658.19 GB)
telemt_user_msgs_from_client{user="hello"} 69581
telemt_user_msgs_to_client{user="hello"} 60103
telemt_user_unique_ips_current{user="hello"} 693
telemt_user_unique_ips_recent_window{user="hello"} 302
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 203330.4 (56h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11244029
telemt_connections_bad_total 990728
telemt_connections_current 1494
telemt_connections_me_current 1494
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 250055
telemt_upstream_connect_attempt_total 119123
telemt_upstream_connect_success_total 117887
telemt_upstream_connect_fail_total 1059
telemt_upstream_connect_attempts_per_request{bucket="1"} 118946
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 69179
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 47094
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1376
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1059
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 73517
telemt_me_reconnect_success_total 3249
telemt_me_reader_eof_total 2945
telemt_me_idle_close_by_peer_total 2942
telemt_me_route_drop_no_conn_total 5309991
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8852072
telemt_me_endpoint_quarantine_total 1380
telemt_me_single_endpoint_outage_enter_total 44
telemt_me_single_endpoint_outage_exit_total 44
telemt_me_single_endpoint_outage_reconnect_attempt_total 46
telemt_me_single_endpoint_outage_reconnect_success_total 44
telemt_me_single_endpoint_quarantine_bypass_total 46
telemt_me_single_endpoint_shadow_rotate_total 1546
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
telemt_me_writers_active_current 43
telemt_desync_total 47141
telemt_desync_full_logged_total 16208
telemt_desync_suppressed_total 30933
telemt_desync_frames_bucket_total{bucket="1_2"} 9566
telemt_desync_frames_bucket_total{bucket="3_10"} 18088
telemt_desync_frames_bucket_total{bucket="gt_10"} 19487
telemt_pool_swap_total 209
telemt_pool_force_close_total 6029
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 682
telemt_me_draining_writers_reap_progress_total 73050
telemt_me_writer_removed_unexpected_total 2962
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7281
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 68778
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5280
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 749
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 67021
telemt_me_writer_teardown_success_total{mode="normal"} 76059
telemt_me_writer_teardown_noop_total 73051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 146954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 148374
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 148793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 149066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149100
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149110
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.357365
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149110
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 682
telemt_me_refill_failed_total 4322
telemt_me_writer_restored_same_endpoint_total 2736
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7369
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8854772
telemt_user_connections_current{user="hello"} 1494
telemt_user_octets_from_client{user="hello"} 198770017813 (185.12 GB)
telemt_user_octets_to_client{user="hello"} 3385078591380 (3.08 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 566
telemt_user_unique_ips_recent_window{user="hello"} 229
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 140166.7 (38h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12014034
telemt_connections_bad_total 492893
telemt_connections_current 1108
telemt_connections_me_current 1108
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4849432
telemt_upstream_connect_attempt_total 68067
telemt_upstream_connect_success_total 67581
telemt_upstream_connect_fail_total 473
telemt_upstream_connect_attempts_per_request{bucket="1"} 68054
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31746
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 239
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 473
telemt_me_reconnect_attempts_total 49314
telemt_me_reconnect_success_total 1955
telemt_me_reader_eof_total 1638
telemt_me_idle_close_by_peer_total 1637
telemt_me_route_drop_no_conn_total 4133711
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5772830
telemt_me_endpoint_quarantine_total 969
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 1082
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
telemt_me_writers_active_current 43
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 32459
telemt_desync_full_logged_total 11092
telemt_desync_suppressed_total 21367
telemt_desync_frames_bucket_total{bucket="1_2"} 6515
telemt_desync_frames_bucket_total{bucket="3_10"} 12784
telemt_desync_frames_bucket_total{bucket="gt_10"} 13160
telemt_pool_swap_total 149
telemt_pool_force_close_total 4221
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 391
telemt_me_draining_writers_reap_progress_total 52944
telemt_me_writer_removed_unexpected_total 1677
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4188
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 50488
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3777
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 444
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 48723
telemt_me_writer_teardown_success_total{mode="normal"} 54676
telemt_me_writer_teardown_noop_total 52951
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 107090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 107400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 107627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 107627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 107627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 107627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 107627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 107627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 107627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 107627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 107627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 107627
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.810260
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 107627
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 391
telemt_me_refill_failed_total 2751
telemt_me_writer_restored_same_endpoint_total 1728
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5764778
telemt_user_connections_current{user="hello"} 1108
telemt_user_octets_from_client{user="hello"} 121504110448 (113.16 GB)
telemt_user_octets_to_client{user="hello"} 2244361552050 (2.04 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 177
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 121137.1 (33h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1667738
telemt_connections_bad_total 37260
telemt_connections_current 872
telemt_connections_me_current 872
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 34941
telemt_upstream_connect_attempt_total 57152
telemt_upstream_connect_success_total 56973
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 57124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29182
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 836
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 2499
telemt_me_reconnect_success_total 1005
telemt_me_reader_eof_total 1001
telemt_me_idle_close_by_peer_total 1001
telemt_me_route_drop_no_conn_total 556709
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1482573
telemt_me_endpoint_quarantine_total 1027
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1001
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
telemt_me_writers_active_current 43
telemt_desync_total 10277
telemt_desync_full_logged_total 2902
telemt_desync_suppressed_total 7375
telemt_desync_frames_bucket_total{bucket="1_2"} 3236
telemt_desync_frames_bucket_total{bucket="3_10"} 3869
telemt_desync_frames_bucket_total{bucket="gt_10"} 3172
telemt_pool_swap_total 131
telemt_pool_force_close_total 3302
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 177
telemt_me_draining_writers_reap_progress_total 48731
telemt_me_writer_removed_unexpected_total 964
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3679
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46060
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3214
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45429
telemt_me_writer_teardown_success_total{mode="normal"} 49739
telemt_me_writer_teardown_noop_total 48735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 97435
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 98206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98474
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98474
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.669376
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98474
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 177
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 860
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 82
telemt_user_connections_total{user="hello"} 1478175
telemt_user_connections_current{user="hello"} 872
telemt_user_octets_from_client{user="hello"} 27373023197 (25.49 GB)
telemt_user_octets_to_client{user="hello"} 610196428955 (568.29 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 315
telemt_user_unique_ips_recent_window{user="hello"} 148
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 203335.0 (56h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13530009
telemt_connections_bad_total 1633935
telemt_connections_current 1301
telemt_connections_me_current 1301
telemt_handshake_timeouts_total 396246
telemt_upstream_connect_attempt_total 81966
telemt_upstream_connect_success_total 81603
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 81829
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 40367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 41131
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 101
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 3218
telemt_me_reconnect_success_total 1615
telemt_me_reader_eof_total 1606
telemt_me_idle_close_by_peer_total 1606
telemt_me_route_drop_no_conn_total 4520887
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 42
telemt_me_route_drop_queue_full_profile_total{profile="high"} 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 10200855
telemt_me_endpoint_quarantine_total 1502
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 1544
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
telemt_me_writers_active_current 46
telemt_desync_total 42821
telemt_desync_full_logged_total 13973
telemt_desync_suppressed_total 28848
telemt_desync_frames_bucket_total{bucket="1_2"} 10437
telemt_desync_frames_bucket_total{bucket="3_10"} 15712
telemt_desync_frames_bucket_total{bucket="gt_10"} 16672
telemt_pool_swap_total 225
telemt_pool_force_close_total 5874
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 699
telemt_me_draining_writers_reap_progress_total 74191
telemt_me_writer_removed_unexpected_total 1536
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5710
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70077
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5700
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68317
telemt_me_writer_teardown_success_total{mode="normal"} 75787
telemt_me_writer_teardown_noop_total 74193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 147339
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 149088
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 149471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 149847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 149967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 149980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 149980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 149980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 149980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 149980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 149980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 149980
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 149980
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.980124
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 149980
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 699
telemt_me_refill_failed_total 86
telemt_me_writer_restored_same_endpoint_total 1422
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 10167326
telemt_user_connections_current{user="hello"} 1301
telemt_user_octets_from_client{user="hello"} 196679551084 (183.17 GB)
telemt_user_octets_to_client{user="hello"} 4532339133472 (4.12 TB)
telemt_user_unique_ips_current{user="hello"} 487
telemt_user_unique_ips_recent_window{user="hello"} 166
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 203331.6 (56h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11847943
telemt_connections_bad_total 1386655
telemt_connections_current 1140
telemt_connections_me_current 1140
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 318960
telemt_upstream_connect_attempt_total 109792
telemt_upstream_connect_success_total 108847
telemt_upstream_connect_fail_total 736
telemt_upstream_connect_attempts_per_request{bucket="1"} 109583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 59103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 46760
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2071
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 736
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 11068
telemt_me_reconnect_success_total 2753
telemt_me_reader_eof_total 2556
telemt_me_idle_close_by_peer_total 2555
telemt_me_seq_mismatch_total 107
telemt_me_route_drop_no_conn_total 5688684
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9120737
telemt_me_endpoint_quarantine_total 1676
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 56
telemt_me_single_endpoint_outage_exit_total 56
telemt_me_single_endpoint_outage_reconnect_attempt_total 56
telemt_me_single_endpoint_outage_reconnect_success_total 54
telemt_me_single_endpoint_quarantine_bypass_total 56
telemt_me_single_endpoint_shadow_rotate_total 1549
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
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
telemt_desync_total 42451
telemt_desync_full_logged_total 13667
telemt_desync_suppressed_total 28784
telemt_desync_frames_bucket_total{bucket="1_2"} 11035
telemt_desync_frames_bucket_total{bucket="3_10"} 15584
telemt_desync_frames_bucket_total{bucket="gt_10"} 15832
telemt_pool_swap_total 215
telemt_pool_force_close_total 5637
telemt_pool_stale_pick_total 390
telemt_me_writer_close_signal_drop_total 683
telemt_me_draining_writers_reap_progress_total 74510
telemt_me_writer_removed_unexpected_total 2592
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 7112
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 70090
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5166
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 68873
telemt_me_writer_teardown_success_total{mode="normal"} 77202
telemt_me_writer_teardown_noop_total 74515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 148996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 150809
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 151348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 151667
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 151717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 151717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 151717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 151717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 151717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 151717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 151717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 151717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 151717
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.674068
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 151717
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 683
telemt_me_refill_failed_total 432
telemt_me_writer_restored_same_endpoint_total 2195
telemt_me_writer_restored_fallback_total 142
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 135
telemt_me_writer_removed_unexpected_minus_restored_total 255
telemt_user_connections_total{user="hello"} 9125191
telemt_user_connections_current{user="hello"} 1140
telemt_user_octets_from_client{user="hello"} 159069727984 (148.15 GB)
telemt_user_octets_to_client{user="hello"} 3572509557990 (3.25 TB)
telemt_user_msgs_from_client{user="hello"} 103592
telemt_user_msgs_to_client{user="hello"} 254638
telemt_user_unique_ips_current{user="hello"} 492
telemt_user_unique_ips_recent_window{user="hello"} 161
```