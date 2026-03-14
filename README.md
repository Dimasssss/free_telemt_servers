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

# Server Metrics 2026-03-14 00:10:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 146213.0 (40h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 588299
telemt_connections_bad_total 20201
telemt_handshake_timeouts_total 12841
telemt_upstream_connect_attempt_total 37233
telemt_upstream_connect_success_total 37047
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 37233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19973
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5165
telemt_me_reconnect_attempts_total 34025
telemt_me_reconnect_success_total 29355
telemt_me_reader_eof_total 31371
telemt_me_idle_close_by_peer_total 31370
telemt_me_route_drop_no_conn_total 193242
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 504451
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1628
telemt_desync_full_logged_total 556
telemt_desync_suppressed_total 1072
telemt_desync_frames_bucket_total{bucket="1_2"} 351
telemt_desync_frames_bucket_total{bucket="3_10"} 608
telemt_desync_frames_bucket_total{bucket="gt_10"} 669
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 29828
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 29339
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 473
telemt_user_connections_total{user="hello"} 504346
telemt_user_connections_current{user="hello"} 175
telemt_user_octets_from_client{user="hello"} 15428998978 (14.37 GB)
telemt_user_octets_to_client{user="hello"} 250149110660 (232.97 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 146106.1 (40h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301754
telemt_connections_bad_total 2223
telemt_handshake_timeouts_total 1930
telemt_upstream_connect_attempt_total 141856
telemt_upstream_connect_success_total 140779
telemt_upstream_connect_fail_total 1076
telemt_upstream_connect_attempts_per_request{bucket="1"} 141855
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106555
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31809
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1076
telemt_me_keepalive_timeout_total 3763
telemt_me_reconnect_attempts_total 155695
telemt_me_reconnect_success_total 30158
telemt_me_reader_eof_total 34872
telemt_me_idle_close_by_peer_total 34872
telemt_me_route_drop_no_conn_total 92896
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182964
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 37
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
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 34367
telemt_me_refill_failed_total 3917
telemt_me_writer_restored_same_endpoint_total 30141
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4209
telemt_user_connections_total{user="hello"} 286076
telemt_user_connections_current{user="hello"} 129
telemt_user_octets_from_client{user="hello"} 2998421251 (2.79 GB)
telemt_user_octets_to_client{user="hello"} 89481790759 (83.34 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 146069.9 (40h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 352869
telemt_connections_bad_total 2763
telemt_handshake_timeouts_total 32602
telemt_upstream_connect_attempt_total 38773
telemt_upstream_connect_success_total 38767
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 38773
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2940
telemt_me_reconnect_attempts_total 32684
telemt_me_reconnect_success_total 31428
telemt_me_reader_eof_total 33759
telemt_me_idle_close_by_peer_total 33759
telemt_me_route_drop_no_conn_total 124840
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 305156
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
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 31799
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 31408
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 371
telemt_user_connections_total{user="hello"} 305058
telemt_user_connections_current{user="hello"} 76
telemt_user_octets_from_client{user="hello"} 12540295636 (11.68 GB)
telemt_user_octets_to_client{user="hello"} 126169445308 (117.50 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 146045.3 (40h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 454156
telemt_connections_bad_total 15362
telemt_handshake_timeouts_total 4253
telemt_upstream_connect_attempt_total 66890
telemt_upstream_connect_success_total 56468
telemt_upstream_connect_fail_total 10422
telemt_upstream_connect_attempts_per_request{bucket="1"} 66890
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 316
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10422
telemt_me_keepalive_timeout_total 5039
telemt_me_reconnect_attempts_total 135110
telemt_me_reconnect_success_total 30135
telemt_me_reader_eof_total 34259
telemt_me_idle_close_by_peer_total 34251
telemt_me_route_drop_no_conn_total 159502
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 384323
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 32
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1684
telemt_desync_full_logged_total 494
telemt_desync_suppressed_total 1190
telemt_desync_frames_bucket_total{bucket="1_2"} 395
telemt_desync_frames_bucket_total{bucket="3_10"} 641
telemt_desync_frames_bucket_total{bucket="gt_10"} 648
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 33783
telemt_me_refill_failed_total 3274
telemt_me_writer_restored_same_endpoint_total 30125
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3648
telemt_user_connections_total{user="hello"} 403165
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 9033606883 (8.41 GB)
telemt_user_octets_to_client{user="hello"} 153945649104 (143.37 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 7
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 96217.0 (26h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 160897
telemt_connections_bad_total 23654
telemt_handshake_timeouts_total 1549
telemt_upstream_connect_attempt_total 35549
telemt_upstream_connect_success_total 35224
telemt_upstream_connect_fail_total 325
telemt_upstream_connect_attempts_per_request{bucket="1"} 35549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18011
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 325
telemt_me_keepalive_timeout_total 1351
telemt_me_reconnect_attempts_total 38950
telemt_me_reconnect_success_total 25540
telemt_me_reader_eof_total 27312
telemt_me_idle_close_by_peer_total 27312
telemt_me_route_drop_no_conn_total 48470
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 125985
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 619
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 474
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 68
telemt_me_writer_removed_unexpected_total 26193
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 25522
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 130836
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 1653030413 (1.54 GB)
telemt_user_octets_to_client{user="hello"} 63170681539 (58.83 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 3
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 146001.4 (40h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 864435
telemt_connections_bad_total 27369
telemt_handshake_timeouts_total 25235
telemt_upstream_connect_attempt_total 30152
telemt_upstream_connect_success_total 29989
telemt_upstream_connect_fail_total 163
telemt_upstream_connect_attempts_per_request{bucket="1"} 30152
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13995
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15953
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 163
telemt_me_keepalive_timeout_total 3404
telemt_me_reconnect_attempts_total 27398
telemt_me_reconnect_success_total 22734
telemt_me_reader_eof_total 24369
telemt_me_idle_close_by_peer_total 24366
telemt_me_route_drop_no_conn_total 411991
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 807269
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 698
telemt_desync_full_logged_total 228
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 220
telemt_pool_swap_total 136
telemt_me_writer_removed_unexpected_total 23177
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22727
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 443
telemt_user_connections_total{user="hello"} 780122
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 13824405340 (12.87 GB)
telemt_user_octets_to_client{user="hello"} 397445756120 (370.15 GB)
telemt_user_unique_ips_current{user="hello"} 122
telemt_user_unique_ips_recent_window{user="hello"} 40
```