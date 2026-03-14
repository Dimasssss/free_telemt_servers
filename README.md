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

# Server Metrics 2026-03-14 07:38:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 173101.3 (48h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 663667
telemt_connections_bad_total 32381
telemt_handshake_timeouts_total 13082
telemt_upstream_connect_attempt_total 44089
telemt_upstream_connect_success_total 43866
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 44089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20059
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23655
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5696
telemt_me_reconnect_attempts_total 39544
telemt_me_reconnect_success_total 34850
telemt_me_reader_eof_total 37271
telemt_me_idle_close_by_peer_total 37270
telemt_me_route_drop_no_conn_total 219578
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 565176
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2134
telemt_desync_full_logged_total 728
telemt_desync_suppressed_total 1406
telemt_desync_frames_bucket_total{bucket="1_2"} 461
telemt_desync_frames_bucket_total{bucket="3_10"} 780
telemt_desync_frames_bucket_total{bucket="gt_10"} 893
telemt_pool_swap_total 160
telemt_me_writer_removed_unexpected_total 35369
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34830
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 519
telemt_user_connections_total{user="hello"} 565059
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 16518414638 (15.38 GB)
telemt_user_octets_to_client{user="hello"} 271178811292 (252.55 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 172994.2 (48h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334211
telemt_connections_bad_total 2328
telemt_handshake_timeouts_total 2573
telemt_upstream_connect_attempt_total 150988
telemt_upstream_connect_success_total 149703
telemt_upstream_connect_fail_total 1285
telemt_upstream_connect_attempts_per_request{bucket="1"} 150988
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 110161
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37117
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2425
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1285
telemt_me_keepalive_timeout_total 4025
telemt_me_reconnect_attempts_total 178358
telemt_me_reconnect_success_total 37766
telemt_me_reader_eof_total 43169
telemt_me_idle_close_by_peer_total 43169
telemt_me_route_drop_no_conn_total 110884
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213327
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 42518
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 37749
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4752
telemt_user_connections_total{user="hello"} 316433
telemt_user_connections_current{user="hello"} 125
telemt_user_octets_from_client{user="hello"} 3283653251 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 103338708867 (96.24 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 172957.5 (48h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 390777
telemt_connections_bad_total 3175
telemt_handshake_timeouts_total 35213
telemt_upstream_connect_attempt_total 45693
telemt_upstream_connect_success_total 45684
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24720
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3490
telemt_me_reconnect_attempts_total 38298
telemt_me_reconnect_success_total 37012
telemt_me_reader_eof_total 39795
telemt_me_idle_close_by_peer_total 39795
telemt_me_route_drop_no_conn_total 141292
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338779
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
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
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 37460
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36991
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 448
telemt_user_connections_total{user="hello"} 338552
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 13574531628 (12.64 GB)
telemt_user_octets_to_client{user="hello"} 136584419296 (127.20 GB)
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 172933.3 (48h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 493098
telemt_connections_bad_total 16265
telemt_handshake_timeouts_total 4537
telemt_upstream_connect_attempt_total 76080
telemt_upstream_connect_success_total 65483
telemt_upstream_connect_fail_total 10597
telemt_upstream_connect_attempts_per_request{bucket="1"} 76080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26588
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10597
telemt_me_keepalive_timeout_total 5427
telemt_me_reconnect_attempts_total 143881
telemt_me_reconnect_success_total 37820
telemt_me_reader_eof_total 42355
telemt_me_idle_close_by_peer_total 42347
telemt_me_route_drop_no_conn_total 178755
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 420149
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1792
telemt_desync_full_logged_total 536
telemt_desync_suppressed_total 1256
telemt_desync_frames_bucket_total{bucket="1_2"} 427
telemt_desync_frames_bucket_total{bucket="3_10"} 681
telemt_desync_frames_bucket_total{bucket="gt_10"} 684
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 41564
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 37810
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3744
telemt_user_connections_total{user="hello"} 439027
telemt_user_connections_current{user="hello"} 162
telemt_user_octets_from_client{user="hello"} 9454874511 (8.81 GB)
telemt_user_octets_to_client{user="hello"} 180118597780 (167.75 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 123104.8 (34h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200787
telemt_connections_bad_total 29639
telemt_handshake_timeouts_total 1753
telemt_upstream_connect_attempt_total 43255
telemt_upstream_connect_success_total 42841
telemt_upstream_connect_fail_total 414
telemt_upstream_connect_attempts_per_request{bucket="1"} 43255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21449
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21250
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 142
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 414
telemt_me_keepalive_timeout_total 2529
telemt_me_reconnect_attempts_total 45273
telemt_me_reconnect_success_total 31839
telemt_me_reader_eof_total 34090
telemt_me_idle_close_by_peer_total 34090
telemt_me_route_drop_no_conn_total 59927
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159006
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 701
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 114
telemt_desync_frames_bucket_total{bucket="3_10"} 335
telemt_desync_frames_bucket_total{bucket="gt_10"} 252
telemt_pool_swap_total 95
telemt_me_writer_removed_unexpected_total 32555
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31821
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 716
telemt_user_connections_total{user="hello"} 163756
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 2421544741 (2.26 GB)
telemt_user_octets_to_client{user="hello"} 76415811427 (71.17 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 172889.3 (48h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 991254
telemt_connections_bad_total 36098
telemt_handshake_timeouts_total 26177
telemt_upstream_connect_attempt_total 35851
telemt_upstream_connect_success_total 35662
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 35851
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 4720
telemt_me_reconnect_attempts_total 31776
telemt_me_reconnect_success_total 27095
telemt_me_reader_eof_total 29081
telemt_me_idle_close_by_peer_total 29078
telemt_me_route_drop_no_conn_total 466521
telemt_me_route_drop_channel_closed_total 25
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 918305
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 164
telemt_me_writer_removed_unexpected_total 27585
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 27088
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 490
telemt_user_connections_total{user="hello"} 890949
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 15245212804 (14.20 GB)
telemt_user_octets_to_client{user="hello"} 447806384468 (417.05 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 57
```