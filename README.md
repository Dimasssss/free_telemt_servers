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

# Server Metrics 2026-03-12 13:29:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 21350.0 (5h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 112961
telemt_connections_bad_total 546
telemt_handshake_timeouts_total 3821
telemt_upstream_connect_attempt_total 5179
telemt_upstream_connect_success_total 5156
telemt_upstream_connect_fail_total 23
telemt_upstream_connect_attempts_per_request{bucket="1"} 5179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2318
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 23
telemt_me_keepalive_timeout_total 242
telemt_me_reconnect_attempts_total 4081
telemt_me_reconnect_success_total 4055
telemt_me_reader_eof_total 4247
telemt_me_idle_close_by_peer_total 4246
telemt_me_route_drop_no_conn_total 31981
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100515
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 475
telemt_desync_full_logged_total 179
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 90
telemt_desync_frames_bucket_total{bucket="3_10"} 187
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 4085
telemt_me_writer_restored_same_endpoint_total 4039
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 30
telemt_user_connections_total{user="hello"} 100479
telemt_user_connections_current{user="hello"} 322
telemt_user_octets_from_client{user="hello"} 1490487160 (1.39 GB)
telemt_user_octets_to_client{user="hello"} 38352134300 (35.72 GB)
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 21243.4 (5h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 45834
telemt_connections_bad_total 336
telemt_handshake_timeouts_total 344
telemt_upstream_connect_attempt_total 6345
telemt_upstream_connect_success_total 6191
telemt_upstream_connect_fail_total 154
telemt_upstream_connect_attempts_per_request{bucket="1"} 6345
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2571
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3603
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 154
telemt_me_keepalive_timeout_total 151
telemt_me_reconnect_attempts_total 20935
telemt_me_reconnect_success_total 5106
telemt_me_reader_eof_total 5683
telemt_me_idle_close_by_peer_total 5683
telemt_me_route_drop_no_conn_total 19969
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43716
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 5626
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 5091
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 520
telemt_user_connections_total{user="hello"} 43715
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 513438368 (489.65 MB)
telemt_user_octets_to_client{user="hello"} 12189227412 (11.35 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 21206.9 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61913
telemt_connections_bad_total 131
telemt_handshake_timeouts_total 683
telemt_upstream_connect_attempt_total 5819
telemt_upstream_connect_success_total 5819
telemt_upstream_connect_attempts_per_request{bucket="1"} 5819
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2968
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 4740
telemt_me_reconnect_success_total 4704
telemt_me_reader_eof_total 4966
telemt_me_idle_close_by_peer_total 4966
telemt_me_route_drop_no_conn_total 21765
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58274
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 4735
telemt_me_writer_restored_same_endpoint_total 4684
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 31
telemt_user_connections_total{user="hello"} 58257
telemt_user_connections_current{user="hello"} 183
telemt_user_octets_from_client{user="hello"} 1793850300 (1.67 GB)
telemt_user_octets_to_client{user="hello"} 35018932048 (32.61 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 21182.5 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79725
telemt_connections_bad_total 1463
telemt_handshake_timeouts_total 367
telemt_upstream_connect_attempt_total 5816
telemt_upstream_connect_success_total 5670
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 5816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2506
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3145
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 234
telemt_me_reconnect_attempts_total 13673
telemt_me_reconnect_success_total 4566
telemt_me_reader_eof_total 4979
telemt_me_idle_close_by_peer_total 4979
telemt_me_route_drop_no_conn_total 26874
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72869
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 222
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 84
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 4903
telemt_me_refill_failed_total 283
telemt_me_writer_restored_same_endpoint_total 4558
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 337
telemt_user_connections_total{user="hello"} 72866
telemt_user_connections_current{user="hello"} 179
telemt_user_octets_from_client{user="hello"} 1211336484 (1.13 GB)
telemt_user_octets_to_client{user="hello"} 33140940492 (30.86 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 21151.9 (5h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 46114
telemt_connections_bad_total 3991
telemt_handshake_timeouts_total 679
telemt_upstream_connect_attempt_total 13687
telemt_upstream_connect_success_total 13438
telemt_upstream_connect_fail_total 249
telemt_upstream_connect_attempts_per_request{bucket="1"} 13687
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9910
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3505
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 249
telemt_me_keepalive_timeout_total 102
telemt_me_reconnect_attempts_total 27290
telemt_me_reconnect_success_total 3649
telemt_me_reader_eof_total 4384
telemt_me_idle_close_by_peer_total 4384
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 11915
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 31630
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 412
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 296
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 342
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4409
telemt_me_refill_failed_total 740
telemt_me_writer_restored_same_endpoint_total 3632
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 760
telemt_user_connections_total{user="hello"} 40317
telemt_user_connections_current{user="hello"} 117
telemt_user_octets_from_client{user="hello"} 324448444 (309.42 MB)
telemt_user_octets_to_client{user="hello"} 10462818285 (9.74 GB)
telemt_user_msgs_from_client{user="hello"} 119621
telemt_user_msgs_to_client{user="hello"} 358210
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 21138.8 (5h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 123339
telemt_connections_bad_total 770
telemt_handshake_timeouts_total 976
telemt_upstream_connect_attempt_total 4386
telemt_upstream_connect_success_total 4364
telemt_upstream_connect_fail_total 22
telemt_upstream_connect_attempts_per_request{bucket="1"} 4386
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 22
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 3303
telemt_me_reconnect_success_total 3275
telemt_me_reader_eof_total 3450
telemt_me_idle_close_by_peer_total 3450
telemt_me_route_drop_no_conn_total 49779
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117619
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 217
telemt_desync_full_logged_total 76
telemt_desync_suppressed_total 141
telemt_desync_frames_bucket_total{bucket="1_2"} 52
telemt_desync_frames_bucket_total{bucket="3_10"} 86
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3315
telemt_me_writer_restored_same_endpoint_total 3268
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 117587
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 2654978964 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 51163665916 (47.65 GB)
telemt_user_unique_ips_current{user="hello"} 123
telemt_user_unique_ips_recent_window{user="hello"} 52
```