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

# Server Metrics 2026-03-13 22:23:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 139793.9 (38h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 577357
telemt_connections_bad_total 17444
telemt_handshake_timeouts_total 12805
telemt_upstream_connect_attempt_total 35496
telemt_upstream_connect_success_total 35318
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 35496
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16188
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18983
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5124
telemt_me_reconnect_attempts_total 32599
telemt_me_reconnect_success_total 27938
telemt_me_reader_eof_total 29842
telemt_me_idle_close_by_peer_total 29841
telemt_me_route_drop_no_conn_total 190560
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 496610
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1585
telemt_desync_full_logged_total 537
telemt_desync_suppressed_total 1048
telemt_desync_frames_bucket_total{bucket="1_2"} 340
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 125
telemt_me_writer_removed_unexpected_total 28399
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 27922
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 461
telemt_user_connections_total{user="hello"} 496504
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 14887927798 (13.87 GB)
telemt_user_octets_to_client{user="hello"} 245138294248 (228.30 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 55
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 139686.8 (38h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294928
telemt_connections_bad_total 2141
telemt_handshake_timeouts_total 1920
telemt_upstream_connect_attempt_total 139376
telemt_upstream_connect_success_total 138351
telemt_upstream_connect_fail_total 1025
telemt_upstream_connect_attempts_per_request{bucket="1"} 139376
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 105702
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1025
telemt_me_keepalive_timeout_total 3707
telemt_me_reconnect_attempts_total 148357
telemt_me_reconnect_success_total 28045
telemt_me_reader_eof_total 32551
telemt_me_idle_close_by_peer_total 32551
telemt_me_route_drop_no_conn_total 88011
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176555
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 27
telemt_me_writer_removed_unexpected_total 32067
telemt_me_refill_failed_total 3754
telemt_me_writer_restored_same_endpoint_total 28028
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4022
telemt_user_connections_total{user="hello"} 279668
telemt_user_connections_current{user="hello"} 135
telemt_user_octets_from_client{user="hello"} 2956431467 (2.75 GB)
telemt_user_octets_to_client{user="hello"} 86582136579 (80.64 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 139650.3 (38h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 343140
telemt_connections_bad_total 2662
telemt_handshake_timeouts_total 28494
telemt_upstream_connect_attempt_total 37161
telemt_upstream_connect_success_total 37156
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 37161
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17121
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19993
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2852
telemt_me_reconnect_attempts_total 31378
telemt_me_reconnect_success_total 30130
telemt_me_reader_eof_total 32335
telemt_me_idle_close_by_peer_total 32335
telemt_me_route_drop_no_conn_total 121887
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 299975
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 129
telemt_me_writer_removed_unexpected_total 30475
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 30110
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 345
telemt_user_connections_total{user="hello"} 299876
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 12354490712 (11.51 GB)
telemt_user_octets_to_client{user="hello"} 124080424752 (115.56 GB)
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 139625.8 (38h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 447057
telemt_connections_bad_total 15282
telemt_handshake_timeouts_total 4236
telemt_upstream_connect_attempt_total 64479
telemt_upstream_connect_success_total 54105
telemt_upstream_connect_fail_total 10374
telemt_upstream_connect_attempts_per_request{bucket="1"} 64479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33682
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20108
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 306
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10374
telemt_me_keepalive_timeout_total 4954
telemt_me_reconnect_attempts_total 130558
telemt_me_reconnect_success_total 28087
telemt_me_reader_eof_total 32074
telemt_me_idle_close_by_peer_total 32067
telemt_me_route_drop_no_conn_total 156135
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 377541
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1601
telemt_desync_full_logged_total 472
telemt_desync_suppressed_total 1129
telemt_desync_frames_bucket_total{bucket="1_2"} 380
telemt_desync_frames_bucket_total{bucket="3_10"} 611
telemt_desync_frames_bucket_total{bucket="gt_10"} 610
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 31641
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 28077
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3554
telemt_user_connections_total{user="hello"} 396383
telemt_user_connections_current{user="hello"} 118
telemt_user_octets_from_client{user="hello"} 8977202515 (8.36 GB)
telemt_user_octets_to_client{user="hello"} 151338916328 (140.95 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 89797.5 (24h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 150668
telemt_connections_bad_total 22390
telemt_handshake_timeouts_total 1538
telemt_upstream_connect_attempt_total 33409
telemt_upstream_connect_success_total 33098
telemt_upstream_connect_fail_total 311
telemt_upstream_connect_attempts_per_request{bucket="1"} 33409
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16979
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 112
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 311
telemt_me_keepalive_timeout_total 1310
telemt_me_reconnect_attempts_total 37130
telemt_me_reconnect_success_total 23733
telemt_me_reader_eof_total 25401
telemt_me_idle_close_by_peer_total 25401
telemt_me_route_drop_no_conn_total 46285
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117140
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 616
telemt_desync_full_logged_total 144
telemt_desync_suppressed_total 472
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 303
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 24376
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 23715
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 643
telemt_user_connections_total{user="hello"} 122034
telemt_user_connections_current{user="hello"} 45
telemt_user_octets_from_client{user="hello"} 1416265549 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 57614206963 (53.66 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 22
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 139581.9 (38h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 841687
telemt_connections_bad_total 27133
telemt_handshake_timeouts_total 25128
telemt_upstream_connect_attempt_total 28689
telemt_upstream_connect_success_total 28537
telemt_upstream_connect_fail_total 152
telemt_upstream_connect_attempts_per_request{bucket="1"} 28689
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15169
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 152
telemt_me_keepalive_timeout_total 3244
telemt_me_reconnect_attempts_total 26256
telemt_me_reconnect_success_total 21603
telemt_me_reader_eof_total 23168
telemt_me_idle_close_by_peer_total 23165
telemt_me_route_drop_no_conn_total 401390
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 787774
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 693
telemt_desync_full_logged_total 226
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 130
telemt_me_writer_removed_unexpected_total 22033
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 21596
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 760629
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 13166936932 (12.26 GB)
telemt_user_octets_to_client{user="hello"} 380205803676 (354.09 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 32
```