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

# Server Metrics 2026-03-12 15:37:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 29022.1 (8h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 154033
telemt_connections_bad_total 1986
telemt_handshake_timeouts_total 4683
telemt_upstream_connect_attempt_total 7038
telemt_upstream_connect_success_total 7011
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 7038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3145
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3860
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 277
telemt_me_reconnect_attempts_total 5538
telemt_me_reconnect_success_total 5498
telemt_me_reader_eof_total 5794
telemt_me_idle_close_by_peer_total 5793
telemt_me_route_drop_no_conn_total 44546
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 132893
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 597
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 372
telemt_desync_frames_bucket_total{bucket="1_2"} 113
telemt_desync_frames_bucket_total{bucket="3_10"} 228
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 5547
telemt_me_writer_restored_same_endpoint_total 5482
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 49
telemt_user_connections_total{user="hello"} 132859
telemt_user_connections_current{user="hello"} 349
telemt_user_octets_from_client{user="hello"} 2226844292 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 50851036272 (47.36 GB)
telemt_user_unique_ips_current{user="hello"} 109
telemt_user_unique_ips_recent_window{user="hello"} 46
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 28915.0 (8h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 64812
telemt_connections_bad_total 453
telemt_handshake_timeouts_total 447
telemt_upstream_connect_attempt_total 9165
telemt_upstream_connect_success_total 8968
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 9165
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3592
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5325
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_timeout_total 193
telemt_me_reconnect_attempts_total 24409
telemt_me_reconnect_success_total 7482
telemt_me_reader_eof_total 8167
telemt_me_idle_close_by_peer_total 8167
telemt_me_route_drop_no_conn_total 28155
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 61728
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 8064
telemt_me_refill_failed_total 528
telemt_me_writer_restored_same_endpoint_total 7467
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 582
telemt_user_connections_total{user="hello"} 61719
telemt_user_connections_current{user="hello"} 128
telemt_user_octets_from_client{user="hello"} 699698000 (667.28 MB)
telemt_user_octets_to_client{user="hello"} 17640937700 (16.43 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 28878.5 (8h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 87848
telemt_connections_bad_total 1434
telemt_handshake_timeouts_total 1679
telemt_upstream_connect_attempt_total 7962
telemt_upstream_connect_success_total 7962
telemt_upstream_connect_attempts_per_request{bucket="1"} 7962
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4100
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 139
telemt_me_reconnect_attempts_total 6497
telemt_me_reconnect_success_total 6440
telemt_me_reader_eof_total 6810
telemt_me_idle_close_by_peer_total 6810
telemt_me_route_drop_no_conn_total 32179
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 81067
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
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 6494
telemt_me_writer_restored_same_endpoint_total 6420
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 81040
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 2087332124 (1.94 GB)
telemt_user_octets_to_client{user="hello"} 43329294976 (40.35 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 28854.2 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 120870
telemt_connections_bad_total 13035
telemt_handshake_timeouts_total 831
telemt_upstream_connect_attempt_total 6933
telemt_upstream_connect_success_total 6738
telemt_upstream_connect_fail_total 195
telemt_upstream_connect_attempts_per_request{bucket="1"} 6933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3071
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3642
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 195
telemt_me_keepalive_timeout_total 300
telemt_me_reconnect_attempts_total 25093
telemt_me_reconnect_success_total 5263
telemt_me_reader_eof_total 6017
telemt_me_idle_close_by_peer_total 6017
telemt_me_route_drop_no_conn_total 41653
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100659
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 350
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 241
telemt_desync_frames_bucket_total{bucket="1_2"} 111
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 111
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5944
telemt_me_refill_failed_total 618
telemt_me_writer_restored_same_endpoint_total 5255
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 681
telemt_user_connections_total{user="hello"} 100540
telemt_user_connections_current{user="hello"} 182
telemt_user_octets_from_client{user="hello"} 1939616620 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 41451323684 (38.60 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 28823.6 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 67748
telemt_connections_bad_total 5592
telemt_handshake_timeouts_total 1074
telemt_upstream_connect_attempt_total 31400
telemt_upstream_connect_success_total 31051
telemt_upstream_connect_fail_total 349
telemt_upstream_connect_attempts_per_request{bucket="1"} 31400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5081
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 349
telemt_me_keepalive_timeout_total 107
telemt_me_reconnect_attempts_total 38287
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4762
telemt_me_idle_close_by_peer_total 4762
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 12612
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33591
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4788
telemt_me_refill_failed_total 1084
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1104
telemt_user_connections_total{user="hello"} 59500
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 530097614 (505.54 MB)
telemt_user_octets_to_client{user="hello"} 18458186056 (17.19 GB)
telemt_user_msgs_from_client{user="hello"} 422561
telemt_user_msgs_to_client{user="hello"} 1738105
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 28810.9 (8h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179380
telemt_connections_bad_total 903
telemt_handshake_timeouts_total 1420
telemt_upstream_connect_attempt_total 6043
telemt_upstream_connect_success_total 6011
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 6043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2813
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 336
telemt_me_reconnect_attempts_total 5622
telemt_me_reconnect_success_total 4558
telemt_me_reader_eof_total 4808
telemt_me_idle_close_by_peer_total 4807
telemt_me_route_drop_no_conn_total 69730
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171706
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 248
telemt_desync_full_logged_total 97
telemt_desync_suppressed_total 151
telemt_desync_frames_bucket_total{bucket="1_2"} 65
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 92
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 4648
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4551
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 171665
telemt_user_connections_current{user="hello"} 401
telemt_user_octets_from_client{user="hello"} 3397483744 (3.16 GB)
telemt_user_octets_to_client{user="hello"} 77813825712 (72.47 GB)
telemt_user_unique_ips_current{user="hello"} 133
telemt_user_unique_ips_recent_window{user="hello"} 63
```