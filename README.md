# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
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

## rdp-onedash.ru
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

# Server Metrics 2026-03-16 12:29:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 137728.1 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 766890
telemt_connections_bad_total 54204
telemt_handshake_timeouts_total 24403
telemt_upstream_connect_attempt_total 31807
telemt_upstream_connect_success_total 31653
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 31807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17491
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 39057
telemt_me_reconnect_success_total 24825
telemt_me_reader_eof_total 26772
telemt_me_idle_close_by_peer_total 26772
telemt_me_route_drop_no_conn_total 611098
telemt_me_route_drop_channel_closed_total 96
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 703594
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3380
telemt_desync_full_logged_total 1265
telemt_desync_suppressed_total 2115
telemt_desync_frames_bucket_total{bucket="1_2"} 707
telemt_desync_frames_bucket_total{bucket="3_10"} 1414
telemt_desync_frames_bucket_total{bucket="gt_10"} 1259
telemt_pool_swap_total 124
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 25540
telemt_me_refill_failed_total 440
telemt_me_writer_restored_same_endpoint_total 24790
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 715
telemt_user_connections_total{user="hello"} 640074
telemt_user_connections_current{user="hello"} 733
telemt_user_octets_from_client{user="hello"} 12901522184 (12.02 GB)
telemt_user_octets_to_client{user="hello"} 369320494052 (343.96 GB)
telemt_user_unique_ips_current{user="hello"} 227
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 137736.1 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 318034
telemt_connections_bad_total 4508
telemt_handshake_timeouts_total 20690
telemt_upstream_connect_attempt_total 36744
telemt_upstream_connect_success_total 36637
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 36744
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19973
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 839
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_keepalive_timeout_total 1697
telemt_me_reconnect_attempts_total 43117
telemt_me_reconnect_success_total 29176
telemt_me_reader_eof_total 31349
telemt_me_idle_close_by_peer_total 31348
telemt_me_route_drop_no_conn_total 150774
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 281104
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 225
telemt_desync_full_logged_total 73
telemt_desync_suppressed_total 152
telemt_desync_frames_bucket_total{bucket="1_2"} 46
telemt_desync_frames_bucket_total{bucket="3_10"} 85
telemt_desync_frames_bucket_total{bucket="gt_10"} 94
telemt_pool_swap_total 113
telemt_me_writer_removed_unexpected_total 30029
telemt_me_refill_failed_total 426
telemt_me_writer_restored_same_endpoint_total 29160
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 853
telemt_user_connections_total{user="hello"} 280792
telemt_user_connections_current{user="hello"} 381
telemt_user_octets_from_client{user="hello"} 5580146629 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 139718111392 (130.12 GB)
telemt_user_msgs_from_client{user="hello"} 994
telemt_user_msgs_to_client{user="hello"} 1709
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 137728.1 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 305505
telemt_connections_bad_total 5977
telemt_handshake_timeouts_total 8950
telemt_upstream_connect_attempt_total 38049
telemt_upstream_connect_success_total 38041
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 38049
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16432
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21548
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 71
telemt_me_reconnect_attempts_total 38572
telemt_me_reconnect_success_total 31131
telemt_me_reader_eof_total 33425
telemt_me_idle_close_by_peer_total 33424
telemt_me_route_drop_no_conn_total 103824
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 250536
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 119
telemt_desync_full_logged_total 46
telemt_desync_suppressed_total 73
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 52
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 31681
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 31123
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 550
telemt_user_connections_total{user="hello"} 250133
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 18930573337 (17.63 GB)
telemt_user_octets_to_client{user="hello"} 130501670380 (121.54 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 137727.6 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 462178
telemt_connections_bad_total 1551
telemt_handshake_timeouts_total 5677
telemt_upstream_connect_attempt_total 31807
telemt_upstream_connect_success_total 31762
telemt_upstream_connect_fail_total 45
telemt_upstream_connect_attempts_per_request{bucket="1"} 31807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16245
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 172
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 45
telemt_me_keepalive_timeout_total 127
telemt_me_reconnect_attempts_total 29920
telemt_me_reconnect_success_total 24915
telemt_me_reader_eof_total 26681
telemt_me_idle_close_by_peer_total 26680
telemt_me_route_drop_no_conn_total 156396
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 426515
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1548
telemt_desync_full_logged_total 516
telemt_desync_suppressed_total 1032
telemt_desync_frames_bucket_total{bucket="1_2"} 309
telemt_desync_frames_bucket_total{bucket="3_10"} 666
telemt_desync_frames_bucket_total{bucket="gt_10"} 573
telemt_pool_swap_total 124
telemt_me_writer_removed_unexpected_total 25405
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 24904
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 426345
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 6620779510 (6.17 GB)
telemt_user_octets_to_client{user="hello"} 162391547716 (151.24 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 127
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 112799.0 (31h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 289262
telemt_connections_bad_total 53203
telemt_handshake_timeouts_total 4515
telemt_upstream_connect_attempt_total 32146
telemt_upstream_connect_success_total 31974
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 32146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17739
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 173
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_keepalive_timeout_total 52
telemt_me_reconnect_attempts_total 121783
telemt_me_reconnect_success_total 26172
telemt_me_reader_eof_total 27802
telemt_me_idle_close_by_peer_total 27802
telemt_me_route_drop_no_conn_total 86658
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 222638
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 102
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 311
telemt_pool_swap_total 94
telemt_me_writer_removed_unexpected_total 26435
telemt_me_refill_failed_total 3067
telemt_me_writer_restored_same_endpoint_total 26068
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 222256
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 2882344161 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 99644401783 (92.80 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 72
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 137727.0 (38h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 993634
telemt_connections_bad_total 77765
telemt_handshake_timeouts_total 12498
telemt_upstream_connect_attempt_total 29129
telemt_upstream_connect_success_total 28977
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 29129
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15284
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 168
telemt_me_reconnect_attempts_total 24735
telemt_me_reconnect_success_total 22109
telemt_me_reader_eof_total 23581
telemt_me_idle_close_by_peer_total 23580
telemt_me_route_drop_no_conn_total 713558
telemt_me_route_drop_channel_closed_total 137
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 966566
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 671
telemt_desync_full_logged_total 205
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 185
telemt_desync_frames_bucket_total{bucket="3_10"} 241
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 123
telemt_me_writer_removed_unexpected_total 22463
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 22082
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 354
telemt_user_connections_total{user="hello"} 825152
telemt_user_connections_current{user="hello"} 795
telemt_user_octets_from_client{user="hello"} 17707463176 (16.49 GB)
telemt_user_octets_to_client{user="hello"} 472362862836 (439.92 GB)
telemt_user_unique_ips_current{user="hello"} 267
telemt_user_unique_ips_recent_window{user="hello"} 101
```