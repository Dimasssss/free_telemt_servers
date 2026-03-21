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

# Server Metrics 2026-03-21 13:21:01 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 60304.3 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1988057
telemt_connections_bad_total 99486
telemt_connections_current 1561
telemt_connections_me_current 1561
telemt_handshake_timeouts_total 72421
telemt_upstream_connect_attempt_total 23174
telemt_upstream_connect_success_total 23059
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 23136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8162
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 30
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 50
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 92
telemt_me_reconnect_attempts_total 1296
telemt_me_reconnect_success_total 530
telemt_me_reader_eof_total 512
telemt_me_idle_close_by_peer_total 512
telemt_me_route_drop_no_conn_total 1489525
telemt_me_route_drop_channel_closed_total 495
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1566344
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_endpoint_quarantine_total 422
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 474
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
telemt_desync_total 6196
telemt_desync_full_logged_total 2131
telemt_desync_suppressed_total 4065
telemt_desync_frames_bucket_total{bucket="1_2"} 1383
telemt_desync_frames_bucket_total{bucket="3_10"} 2351
telemt_desync_frames_bucket_total{bucket="gt_10"} 2462
telemt_pool_swap_total 65
telemt_pool_force_close_total 1927
telemt_pool_stale_pick_total 14
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 20734
telemt_me_writer_removed_unexpected_total 493
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1706
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19349
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1857
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18807
telemt_me_writer_teardown_success_total{mode="normal"} 21055
telemt_me_writer_teardown_noop_total 20739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 35840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37993
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40972
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41579
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41794
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 164.159335
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41794
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 458
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 1565197
telemt_user_connections_current{user="hello"} 1561
telemt_user_octets_from_client{user="hello"} 23414035939 (21.81 GB)
telemt_user_octets_to_client{user="hello"} 407333263451 (379.36 GB)
telemt_user_msgs_from_client{user="hello"} 295
telemt_user_msgs_to_client{user="hello"} 249
telemt_user_unique_ips_current{user="hello"} 578
telemt_user_unique_ips_recent_window{user="hello"} 238
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 34.1 (0h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_upstream_connect_attempt_total 88
telemt_upstream_connect_success_total 84
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 87
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 1
telemt_me_reconnect_success_total 1
telemt_me_endpoint_quarantine_total 5
telemt_me_single_endpoint_shadow_rotate_total 5
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 43
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_draining_writers_reap_progress_total 5
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5
telemt_me_writer_teardown_success_total{mode="normal"} 5
telemt_me_writer_teardown_noop_total 5
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.000463
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 60302.3 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3922779
telemt_connections_bad_total 389314
telemt_connections_current 5381
telemt_connections_me_current 5381
telemt_handshake_timeouts_total 151667
telemt_upstream_connect_attempt_total 22698
telemt_upstream_connect_success_total 22663
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 22668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12315
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 848
telemt_me_reconnect_success_total 479
telemt_me_reader_eof_total 475
telemt_me_idle_close_by_peer_total 475
telemt_me_route_drop_no_conn_total 1965091
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3156310
telemt_me_endpoint_quarantine_total 383
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 459
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
telemt_me_writers_active_current 52
telemt_desync_total 13343
telemt_desync_full_logged_total 4516
telemt_desync_suppressed_total 8827
telemt_desync_frames_bucket_total{bucket="1_2"} 2832
telemt_desync_frames_bucket_total{bucket="3_10"} 5241
telemt_desync_frames_bucket_total{bucket="gt_10"} 5270
telemt_pool_swap_total 64
telemt_pool_force_close_total 2022
telemt_pool_stale_pick_total 16
telemt_me_writer_close_signal_drop_total 308
telemt_me_draining_writers_reap_progress_total 20625
telemt_me_writer_removed_unexpected_total 458
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1757
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19135
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 18
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1871
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 151
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18603
telemt_me_writer_teardown_success_total{mode="normal"} 20892
telemt_me_writer_teardown_noop_total 20643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 38355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41457
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41535
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 62.506781
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41535
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 308
telemt_me_refill_failed_total 18
telemt_me_writer_restored_same_endpoint_total 431
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 3152295
telemt_user_connections_current{user="hello"} 5381
telemt_user_octets_from_client{user="hello"} 51769398148 (48.21 GB)
telemt_user_octets_to_client{user="hello"} 1086243420800 (1011.64 GB)
telemt_user_unique_ips_current{user="hello"} 1992
telemt_user_unique_ips_recent_window{user="hello"} 688
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 60303.3 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3191851
telemt_connections_bad_total 347068
telemt_connections_current 3685
telemt_connections_me_current 3685
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 122536
telemt_upstream_connect_attempt_total 27322
telemt_upstream_connect_success_total 27048
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 27182
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14081
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 476
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 76
telemt_me_reconnect_attempts_total 1154
telemt_me_reconnect_success_total 538
telemt_me_reader_eof_total 501
telemt_me_idle_close_by_peer_total 501
telemt_me_route_drop_no_conn_total 998568
telemt_me_route_drop_channel_closed_total 82
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2302202
telemt_me_endpoint_quarantine_total 393
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 459
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
telemt_desync_total 10593
telemt_desync_full_logged_total 3591
telemt_desync_suppressed_total 7002
telemt_desync_frames_bucket_total{bucket="1_2"} 2642
telemt_desync_frames_bucket_total{bucket="3_10"} 4081
telemt_desync_frames_bucket_total{bucket="gt_10"} 3870
telemt_pool_swap_total 65
telemt_pool_force_close_total 1825
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 154
telemt_me_draining_writers_reap_progress_total 20030
telemt_me_writer_removed_unexpected_total 488
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1691
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18848
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1704
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 121
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18205
telemt_me_writer_teardown_success_total{mode="normal"} 20539
telemt_me_writer_teardown_noop_total 20031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 39976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40173
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40524
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40568
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40570
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.442980
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40570
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 154
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 453
telemt_me_writer_restored_fallback_total 6
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 2303043
telemt_user_connections_current{user="hello"} 3685
telemt_user_octets_from_client{user="hello"} 43214060293 (40.25 GB)
telemt_user_octets_to_client{user="hello"} 1089128636439 (1014.33 GB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1455
telemt_user_unique_ips_recent_window{user="hello"} 554
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 60267.4 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3115119
telemt_connections_bad_total 334454
telemt_connections_current 3625
telemt_connections_me_current 3625
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 90599
telemt_upstream_connect_attempt_total 32528
telemt_upstream_connect_success_total 32301
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 32434
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13816
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 842
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 1276
telemt_me_reconnect_success_total 616
telemt_me_reader_eof_total 559
telemt_me_idle_close_by_peer_total 559
telemt_me_route_drop_no_conn_total 953774
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2274554
telemt_me_endpoint_quarantine_total 437
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 451
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
telemt_desync_total 10595
telemt_desync_full_logged_total 3525
telemt_desync_suppressed_total 7070
telemt_desync_frames_bucket_total{bucket="1_2"} 2694
telemt_desync_frames_bucket_total{bucket="3_10"} 4018
telemt_desync_frames_bucket_total{bucket="gt_10"} 3883
telemt_pool_swap_total 63
telemt_pool_force_close_total 1779
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 207
telemt_me_draining_writers_reap_progress_total 21389
telemt_me_writer_removed_unexpected_total 533
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1804
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20152
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1619
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 160
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19610
telemt_me_writer_teardown_success_total{mode="normal"} 21956
telemt_me_writer_teardown_noop_total 21393
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 42987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43349
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.400499
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43349
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 207
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 537
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_user_connections_total{user="hello"} 2279455
telemt_user_connections_current{user="hello"} 3625
telemt_user_octets_from_client{user="hello"} 50739630873 (47.25 GB)
telemt_user_octets_to_client{user="hello"} 1084428429632 (1009.95 GB)
telemt_user_msgs_from_client{user="hello"} 42436
telemt_user_msgs_to_client{user="hello"} 111361
telemt_user_unique_ips_current{user="hello"} 1440
telemt_user_unique_ips_recent_window{user="hello"} 530
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 60306.7 (16h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10510577
telemt_connections_bad_total 716031
telemt_connections_current 5710
telemt_connections_me_current 5710
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 337199
telemt_upstream_connect_attempt_total 89845
telemt_upstream_connect_success_total 84619
telemt_upstream_connect_fail_total 4331
telemt_upstream_connect_attempts_per_request{bucket="1"} 88950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 61087
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20407
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3125
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4331
telemt_me_keepalive_timeout_total 73
telemt_me_reconnect_attempts_total 3535
telemt_me_reconnect_success_total 1228
telemt_me_reader_eof_total 882
telemt_me_idle_close_by_peer_total 881
telemt_me_route_drop_no_conn_total 19458640
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8637531
telemt_me_endpoint_quarantine_total 450
telemt_me_single_endpoint_outage_enter_total 67
telemt_me_single_endpoint_outage_exit_total 67
telemt_me_single_endpoint_outage_reconnect_attempt_total 152
telemt_me_single_endpoint_outage_reconnect_success_total 29
telemt_me_single_endpoint_quarantine_bypass_total 152
telemt_me_single_endpoint_shadow_rotate_total 472
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_me_writers_active_current 86
telemt_desync_total 16249
telemt_desync_full_logged_total 5186
telemt_desync_suppressed_total 11063
telemt_desync_frames_bucket_total{bucket="1_2"} 3451
telemt_desync_frames_bucket_total{bucket="3_10"} 7125
telemt_desync_frames_bucket_total{bucket="gt_10"} 5673
telemt_pool_swap_total 60
telemt_pool_force_close_total 1906
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 395
telemt_me_draining_writers_reap_progress_total 19618
telemt_me_writer_removed_unexpected_total 1192
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2552
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18141
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1632
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 274
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17712
telemt_me_writer_teardown_success_total{mode="normal"} 20693
telemt_me_writer_teardown_noop_total 19627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 38858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 39666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40145
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40300
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40320
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.438680
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40320
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 395
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 868
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 63
telemt_me_writer_removed_unexpected_minus_restored_total 316
telemt_user_connections_total{user="hello"} 8695157
telemt_user_connections_current{user="hello"} 5710
telemt_user_octets_from_client{user="hello"} 66605004985 (62.03 GB)
telemt_user_octets_to_client{user="hello"} 715048286060 (665.94 GB)
telemt_user_msgs_from_client{user="hello"} 173886
telemt_user_msgs_to_client{user="hello"} 472410
telemt_user_unique_ips_current{user="hello"} 2034
telemt_user_unique_ips_recent_window{user="hello"} 1051
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 60274.3 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3141120
telemt_connections_bad_total 367099
telemt_connections_current 4030
telemt_connections_me_current 4030
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 69160
telemt_upstream_connect_attempt_total 25894
telemt_upstream_connect_success_total 25609
telemt_upstream_connect_fail_total 255
telemt_upstream_connect_attempts_per_request{bucket="1"} 25864
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13274
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 62
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 255
telemt_me_reconnect_attempts_total 2525
telemt_me_reconnect_success_total 896
telemt_me_reader_eof_total 888
telemt_me_idle_close_by_peer_total 888
telemt_me_route_drop_no_conn_total 1194012
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 33
telemt_me_route_drop_queue_full_profile_total{profile="high"} 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2389104
telemt_me_endpoint_quarantine_total 374
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 457
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
telemt_me_writers_active_current 89
telemt_desync_total 11193
telemt_desync_full_logged_total 3884
telemt_desync_suppressed_total 7309
telemt_desync_frames_bucket_total{bucket="1_2"} 2176
telemt_desync_frames_bucket_total{bucket="3_10"} 4460
telemt_desync_frames_bucket_total{bucket="gt_10"} 4557
telemt_pool_swap_total 60
telemt_pool_force_close_total 1687
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 158
telemt_me_draining_writers_reap_progress_total 21580
telemt_me_writer_removed_unexpected_total 859
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2092
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20376
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1497
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 190
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19893
telemt_me_writer_teardown_success_total{mode="normal"} 22468
telemt_me_writer_teardown_noop_total 21581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 43604
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44021
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44049
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44049
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.483629
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44049
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 158
telemt_me_refill_failed_total 89
telemt_me_writer_restored_same_endpoint_total 761
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 2373876
telemt_user_connections_current{user="hello"} 4030
telemt_user_octets_from_client{user="hello"} 47678088784 (44.40 GB)
telemt_user_octets_to_client{user="hello"} 1034906189566 (963.83 GB)
telemt_user_msgs_from_client{user="hello"} 7339
telemt_user_msgs_to_client{user="hello"} 11522
telemt_user_unique_ips_current{user="hello"} 1661
telemt_user_unique_ips_recent_window{user="hello"} 571
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 60268.8 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4795959
telemt_connections_bad_total 236845
telemt_connections_current 3357
telemt_connections_me_current 3357
telemt_handshake_timeouts_total 2117758
telemt_upstream_connect_attempt_total 23878
telemt_upstream_connect_success_total 23844
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 23847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12899
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 991
telemt_me_reconnect_success_total 427
telemt_me_reader_eof_total 435
telemt_me_idle_close_by_peer_total 435
telemt_me_route_drop_no_conn_total 1085955
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2149259
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 2
telemt_me_single_endpoint_outage_exit_total 2
telemt_me_single_endpoint_outage_reconnect_attempt_total 2
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 2
telemt_me_single_endpoint_shadow_rotate_total 467
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
telemt_desync_total 10263
telemt_desync_full_logged_total 3645
telemt_desync_suppressed_total 6618
telemt_desync_frames_bucket_total{bucket="1_2"} 1894
telemt_desync_frames_bucket_total{bucket="3_10"} 4080
telemt_desync_frames_bucket_total{bucket="gt_10"} 4289
telemt_pool_swap_total 65
telemt_pool_force_close_total 1658
telemt_me_writer_close_signal_drop_total 146
telemt_me_draining_writers_reap_progress_total 21376
telemt_me_writer_removed_unexpected_total 417
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1457
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20363
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1601
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 57
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19718
telemt_me_writer_teardown_success_total{mode="normal"} 21820
telemt_me_writer_teardown_noop_total 21376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43182
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43196
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.472089
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43196
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 146
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 372
telemt_me_writer_restored_fallback_total 2
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 2142493
telemt_user_connections_current{user="hello"} 3357
telemt_user_octets_from_client{user="hello"} 41747134748 (38.88 GB)
telemt_user_octets_to_client{user="hello"} 1003856226268 (934.91 GB)
telemt_user_unique_ips_current{user="hello"} 1318
telemt_user_unique_ips_recent_window{user="hello"} 561
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 58260.1 (16h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1034835
telemt_connections_bad_total 132215
telemt_connections_current 773
telemt_connections_me_current 773
telemt_handshake_timeouts_total 360455
telemt_upstream_connect_attempt_total 27457
telemt_upstream_connect_success_total 27455
telemt_upstream_connect_attempts_per_request{bucket="1"} 27455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11308
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16065
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1185
telemt_me_reconnect_success_total 457
telemt_me_reader_eof_total 454
telemt_me_idle_close_by_peer_total 454
telemt_me_route_drop_no_conn_total 215205
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472911
telemt_me_endpoint_quarantine_total 535
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 492
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
telemt_desync_total 3160
telemt_desync_full_logged_total 1178
telemt_desync_suppressed_total 1982
telemt_desync_frames_bucket_total{bucket="1_2"} 550
telemt_desync_frames_bucket_total{bucket="3_10"} 1125
telemt_desync_frames_bucket_total{bucket="gt_10"} 1485
telemt_pool_swap_total 64
telemt_pool_force_close_total 1441
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 102
telemt_me_draining_writers_reap_progress_total 24611
telemt_me_writer_removed_unexpected_total 429
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1812
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23238
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1438
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23170
telemt_me_writer_teardown_success_total{mode="normal"} 25050
telemt_me_writer_teardown_noop_total 24611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 49653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 49661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 49661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 49661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 49661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 49661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 49661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 49661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 49661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 49661
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.264648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 49661
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 102
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 370
telemt_me_writer_restored_fallback_total 5
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 472716
telemt_user_connections_current{user="hello"} 773
telemt_user_octets_from_client{user="hello"} 8468139351 (7.89 GB)
telemt_user_octets_to_client{user="hello"} 181035941165 (168.60 GB)
telemt_user_msgs_from_client{user="hello"} 804
telemt_user_msgs_to_client{user="hello"} 1943
telemt_user_unique_ips_current{user="hello"} 302
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 60278.6 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3393770
telemt_connections_bad_total 321247
telemt_connections_current 4554
telemt_connections_me_current 4554
telemt_handshake_timeouts_total 100817
telemt_upstream_connect_attempt_total 24677
telemt_upstream_connect_success_total 24577
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 24646
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12220
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12326
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 998
telemt_me_reconnect_success_total 555
telemt_me_reader_eof_total 519
telemt_me_idle_close_by_peer_total 519
telemt_me_route_drop_no_conn_total 975461
telemt_me_route_drop_channel_closed_total 24
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2679247
telemt_me_endpoint_quarantine_total 457
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 463
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
telemt_desync_total 10817
telemt_desync_full_logged_total 3552
telemt_desync_suppressed_total 7265
telemt_desync_frames_bucket_total{bucket="1_2"} 2574
telemt_desync_frames_bucket_total{bucket="3_10"} 4026
telemt_desync_frames_bucket_total{bucket="gt_10"} 4217
telemt_pool_swap_total 66
telemt_pool_force_close_total 1703
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 183
telemt_me_draining_writers_reap_progress_total 22177
telemt_me_writer_removed_unexpected_total 510
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1713
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20972
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1672
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 31
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20474
telemt_me_writer_teardown_success_total{mode="normal"} 22685
telemt_me_writer_teardown_noop_total 22177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 44649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 44729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 44839
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 44862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44862
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44862
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.619093
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44862
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 183
telemt_me_refill_failed_total 22
telemt_me_writer_restored_same_endpoint_total 494
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 11
telemt_user_connections_total{user="hello"} 2671977
telemt_user_connections_current{user="hello"} 4554
telemt_user_octets_from_client{user="hello"} 56338352120 (52.47 GB)
telemt_user_octets_to_client{user="hello"} 1260034450208 (1.15 TB)
telemt_user_unique_ips_current{user="hello"} 1668
telemt_user_unique_ips_recent_window{user="hello"} 619
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 60275.3 (16h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3047180
telemt_connections_bad_total 254486
telemt_connections_current 4012
telemt_connections_me_current 4012
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 89440
telemt_upstream_connect_attempt_total 40921
telemt_upstream_connect_success_total 40656
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 40875
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25529
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14024
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 587
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_reconnect_attempts_total 3428
telemt_me_reconnect_success_total 739
telemt_me_reader_eof_total 641
telemt_me_idle_close_by_peer_total 641
telemt_me_seq_mismatch_total 30
telemt_me_route_drop_no_conn_total 1013888
telemt_me_route_drop_channel_closed_total 77
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2450350
telemt_me_endpoint_quarantine_total 513
telemt_me_single_endpoint_outage_enter_total 16
telemt_me_single_endpoint_outage_exit_total 16
telemt_me_single_endpoint_outage_reconnect_attempt_total 16
telemt_me_single_endpoint_outage_reconnect_success_total 16
telemt_me_single_endpoint_quarantine_bypass_total 16
telemt_me_single_endpoint_shadow_rotate_total 464
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
telemt_desync_total 9478
telemt_desync_full_logged_total 3230
telemt_desync_suppressed_total 6248
telemt_desync_frames_bucket_total{bucket="1_2"} 2420
telemt_desync_frames_bucket_total{bucket="3_10"} 3500
telemt_desync_frames_bucket_total{bucket="gt_10"} 3558
telemt_pool_swap_total 65
telemt_pool_force_close_total 1647
telemt_me_writer_close_signal_drop_total 169
telemt_me_draining_writers_reap_progress_total 21376
telemt_me_writer_removed_unexpected_total 653
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2021
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20038
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1539
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 108
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19729
telemt_me_writer_teardown_success_total{mode="normal"} 22059
telemt_me_writer_teardown_noop_total 21377
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 42780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 43171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 43322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 43428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 43436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 43436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 43436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 43436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 43436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 43436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 43436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 43436
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.791585
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 43436
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 169
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 563
telemt_me_writer_restored_fallback_total 39
telemt_me_async_recovery_trigger_total 53
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2459839
telemt_user_connections_current{user="hello"} 4012
telemt_user_octets_from_client{user="hello"} 45309237393 (42.20 GB)
telemt_user_octets_to_client{user="hello"} 1076173225080 (1002.26 GB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1450
telemt_user_unique_ips_recent_window{user="hello"} 533
```