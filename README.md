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

# Server Metrics 2026-03-12 17:34:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 36090.6 (10h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188211
telemt_connections_bad_total 2414
telemt_handshake_timeouts_total 4934
telemt_upstream_connect_attempt_total 9210
telemt_upstream_connect_success_total 9176
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 9210
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4064
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 369
telemt_me_reconnect_attempts_total 9472
telemt_me_reconnect_success_total 7309
telemt_me_reader_eof_total 7711
telemt_me_idle_close_by_peer_total 7710
telemt_me_route_drop_no_conn_total 54645
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159670
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 628
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 393
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 238
telemt_desync_frames_bucket_total{bucket="gt_10"} 270
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7452
telemt_me_refill_failed_total 66
telemt_me_writer_restored_same_endpoint_total 7293
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 159632
telemt_user_connections_current{user="hello"} 285
telemt_user_octets_from_client{user="hello"} 2878102768 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 66983445280 (62.38 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 35984.6 (9h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 78990
telemt_connections_bad_total 467
telemt_handshake_timeouts_total 653
telemt_upstream_connect_attempt_total 10985
telemt_upstream_connect_success_total 10746
telemt_upstream_connect_fail_total 239
telemt_upstream_connect_attempts_per_request{bucket="1"} 10985
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4305
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6354
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 239
telemt_me_keepalive_timeout_total 316
telemt_me_reconnect_attempts_total 36110
telemt_me_reconnect_success_total 8942
telemt_me_reader_eof_total 9961
telemt_me_idle_close_by_peer_total 9961
telemt_me_route_drop_no_conn_total 34777
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75051
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
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
telemt_me_writer_removed_unexpected_total 9860
telemt_me_refill_failed_total 848
telemt_me_writer_restored_same_endpoint_total 8927
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 918
telemt_user_connections_total{user="hello"} 75034
telemt_user_connections_current{user="hello"} 123
telemt_user_octets_from_client{user="hello"} 824974748 (786.76 MB)
telemt_user_octets_to_client{user="hello"} 20486701356 (19.08 GB)
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 35948.0 (9h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 106573
telemt_connections_bad_total 1507
telemt_handshake_timeouts_total 2083
telemt_upstream_connect_attempt_total 9869
telemt_upstream_connect_success_total 9869
telemt_upstream_connect_attempts_per_request{bucket="1"} 9869
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4771
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5088
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 224
telemt_me_reconnect_attempts_total 8079
telemt_me_reconnect_success_total 8008
telemt_me_reader_eof_total 8483
telemt_me_idle_close_by_peer_total 8483
telemt_me_route_drop_no_conn_total 39767
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98644
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 8082
telemt_me_writer_restored_same_endpoint_total 7988
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 98617
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2340281244 (2.18 GB)
telemt_user_octets_to_client{user="hello"} 52440461240 (48.84 GB)
telemt_user_unique_ips_current{user="hello"} 69
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 35923.8 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 146005
telemt_connections_bad_total 13068
telemt_handshake_timeouts_total 1091
telemt_upstream_connect_attempt_total 7826
telemt_upstream_connect_success_total 7583
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 7826
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_timeout_total 362
telemt_me_reconnect_attempts_total 33853
telemt_me_reconnect_success_total 5761
telemt_me_reader_eof_total 6777
telemt_me_idle_close_by_peer_total 6777
telemt_me_route_drop_no_conn_total 52685
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 124568
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 422
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 299
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 155
telemt_desync_frames_bucket_total{bucket="gt_10"} 148
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 6705
telemt_me_refill_failed_total 876
telemt_me_writer_restored_same_endpoint_total 5753
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 944
telemt_user_connections_total{user="hello"} 124450
telemt_user_connections_current{user="hello"} 146
telemt_user_octets_from_client{user="hello"} 2222045576 (2.07 GB)
telemt_user_octets_to_client{user="hello"} 51974094980 (48.40 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 35892.8 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88936
telemt_connections_bad_total 9433
telemt_handshake_timeouts_total 1157
telemt_upstream_connect_attempt_total 46997
telemt_upstream_connect_success_total 46560
telemt_upstream_connect_fail_total 437
telemt_upstream_connect_attempts_per_request{bucket="1"} 46997
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 39702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6818
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 437
telemt_me_keepalive_timeout_total 138
telemt_me_reconnect_attempts_total 49245
telemt_me_reconnect_success_total 3721
telemt_me_reader_eof_total 5141
telemt_me_idle_close_by_peer_total 5141
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 13293
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35028
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 12
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
telemt_me_writer_removed_unexpected_total 5169
telemt_me_refill_failed_total 1425
telemt_me_writer_restored_same_endpoint_total 3704
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1448
telemt_user_connections_total{user="hello"} 76049
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 705291720 (672.62 MB)
telemt_user_octets_to_client{user="hello"} 22699648033 (21.14 GB)
telemt_user_msgs_from_client{user="hello"} 652990
telemt_user_msgs_to_client{user="hello"} 2489815
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 35880.7 (9h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 229107
telemt_connections_bad_total 1112
telemt_handshake_timeouts_total 1854
telemt_upstream_connect_attempt_total 7676
telemt_upstream_connect_success_total 7638
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 7676
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3556
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4072
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_timeout_total 440
telemt_me_reconnect_attempts_total 9420
telemt_me_reconnect_success_total 5821
telemt_me_reader_eof_total 6201
telemt_me_idle_close_by_peer_total 6200
telemt_me_route_drop_no_conn_total 104900
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 228780
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 6010
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 5814
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 218715
telemt_user_connections_current{user="hello"} 471
telemt_user_octets_from_client{user="hello"} 3902286484 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 99043372552 (92.24 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 58
```