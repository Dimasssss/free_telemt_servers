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

# Server Metrics 2026-03-15 23:08:23 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 89634.2 (24h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 401192
telemt_connections_bad_total 5251
telemt_handshake_timeouts_total 13983
telemt_upstream_connect_attempt_total 21396
telemt_upstream_connect_success_total 21293
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 21396
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9419
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11827
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 20249
telemt_me_reconnect_success_total 16842
telemt_me_reader_eof_total 17975
telemt_me_idle_close_by_peer_total 17975
telemt_me_route_drop_no_conn_total 487799
telemt_me_route_drop_channel_closed_total 78
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 427999
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2105
telemt_desync_full_logged_total 830
telemt_desync_suppressed_total 1275
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 808
telemt_desync_frames_bucket_total{bucket="gt_10"} 891
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 17132
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 16808
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 367061
telemt_user_connections_current{user="hello"} 234
telemt_user_octets_from_client{user="hello"} 8029755116 (7.48 GB)
telemt_user_octets_to_client{user="hello"} 275140605664 (256.24 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 89640.4 (24h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 167620
telemt_connections_bad_total 2902
telemt_handshake_timeouts_total 14004
telemt_upstream_connect_attempt_total 24423
telemt_upstream_connect_success_total 24348
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 24423
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10598
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13142
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 608
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1305
telemt_me_reconnect_attempts_total 26373
telemt_me_reconnect_success_total 19479
telemt_me_reader_eof_total 20838
telemt_me_idle_close_by_peer_total 20837
telemt_me_route_drop_no_conn_total 67989
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143873
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 16
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 74
telemt_me_writer_removed_unexpected_total 19984
telemt_me_refill_failed_total 208
telemt_me_writer_restored_same_endpoint_total 19463
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 505
telemt_user_connections_total{user="hello"} 144143
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 3338071845 (3.11 GB)
telemt_user_octets_to_client{user="hello"} 76224652312 (70.99 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 89632.9 (24h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166488
telemt_connections_bad_total 1768
telemt_handshake_timeouts_total 3474
telemt_upstream_connect_attempt_total 25556
telemt_upstream_connect_success_total 25548
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 25556
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11062
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14438
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 35
telemt_me_reconnect_attempts_total 28409
telemt_me_reconnect_success_total 21035
telemt_me_reader_eof_total 22614
telemt_me_idle_close_by_peer_total 22613
telemt_me_route_drop_no_conn_total 65608
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148621
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 60
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 36
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 30
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 21468
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 21027
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 433
telemt_user_connections_total{user="hello"} 148503
telemt_user_connections_current{user="hello"} 95
telemt_user_octets_from_client{user="hello"} 13084000576 (12.19 GB)
telemt_user_octets_to_client{user="hello"} 97108539484 (90.44 GB)
telemt_user_unique_ips_current{user="hello"} 43
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 89632.7 (24h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 243938
telemt_connections_bad_total 1202
telemt_handshake_timeouts_total 1616
telemt_upstream_connect_attempt_total 20913
telemt_upstream_connect_success_total 20894
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 20913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10001
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10798
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_keepalive_timeout_total 20
telemt_me_reconnect_attempts_total 16541
telemt_me_reconnect_success_total 16441
telemt_me_reader_eof_total 17523
telemt_me_idle_close_by_peer_total 17523
telemt_me_route_drop_no_conn_total 88808
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225277
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 851
telemt_desync_full_logged_total 297
telemt_desync_suppressed_total 554
telemt_desync_frames_bucket_total{bucket="1_2"} 173
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 317
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 16634
telemt_me_writer_restored_same_endpoint_total 16430
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 193
telemt_user_connections_total{user="hello"} 225189
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 4089406992 (3.81 GB)
telemt_user_octets_to_client{user="hello"} 106370372616 (99.07 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 64704.2 (17h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153017
telemt_connections_bad_total 28308
telemt_handshake_timeouts_total 2814
telemt_upstream_connect_attempt_total 18608
telemt_upstream_connect_success_total 18500
telemt_upstream_connect_fail_total 108
telemt_upstream_connect_attempts_per_request{bucket="1"} 18608
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10059
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 108
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 109577
telemt_me_reconnect_success_total 15118
telemt_me_reader_eof_total 15969
telemt_me_idle_close_by_peer_total 15969
telemt_me_route_drop_no_conn_total 48976
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 117568
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 337
telemt_desync_full_logged_total 78
telemt_desync_suppressed_total 259
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 127
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 15228
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 15014
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 117694
telemt_user_connections_current{user="hello"} 32
telemt_user_octets_from_client{user="hello"} 1769080173 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 42621515715 (39.69 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 89631.9 (24h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 605503
telemt_connections_bad_total 58577
telemt_handshake_timeouts_total 4707
telemt_upstream_connect_attempt_total 18952
telemt_upstream_connect_success_total 18846
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 18952
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9014
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9791
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 62
telemt_me_reconnect_attempts_total 15681
telemt_me_reconnect_success_total 14366
telemt_me_reader_eof_total 15297
telemt_me_idle_close_by_peer_total 15297
telemt_me_route_drop_no_conn_total 535383
telemt_me_route_drop_channel_closed_total 95
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 638417
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 324
telemt_desync_full_logged_total 91
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 95
telemt_desync_frames_bucket_total{bucket="gt_10"} 60
telemt_pool_swap_total 80
telemt_me_writer_removed_unexpected_total 14567
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 14339
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 507317
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 12456126684 (11.60 GB)
telemt_user_octets_to_client{user="hello"} 313430738336 (291.91 GB)
telemt_user_unique_ips_current{user="hello"} 129
telemt_user_unique_ips_recent_window{user="hello"} 37
```