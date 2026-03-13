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

# Server Metrics 2026-03-13 06:42:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 83333.3 (23h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 315648
telemt_connections_bad_total 3130
telemt_handshake_timeouts_total 6716
telemt_upstream_connect_attempt_total 21001
telemt_upstream_connect_success_total 20903
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 21001
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9422
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11433
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1621
telemt_me_reconnect_attempts_total 20222
telemt_me_reconnect_success_total 16719
telemt_me_reader_eof_total 17877
telemt_me_idle_close_by_peer_total 17876
telemt_me_route_drop_no_conn_total 98285
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 267007
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 928
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 584
telemt_desync_frames_bucket_total{bucket="1_2"} 186
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 17009
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16703
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 290
telemt_user_connections_total{user="hello"} 266938
telemt_user_connections_current{user="hello"} 291
telemt_user_octets_from_client{user="hello"} 4526762160 (4.22 GB)
telemt_user_octets_to_client{user="hello"} 126656812988 (117.96 GB)
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 83226.1 (23h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144652
telemt_connections_bad_total 1422
telemt_handshake_timeouts_total 1066
telemt_upstream_connect_attempt_total 43362
telemt_upstream_connect_success_total 42797
telemt_upstream_connect_fail_total 565
telemt_upstream_connect_attempts_per_request{bucket="1"} 43362
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17005
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 565
telemt_me_keepalive_timeout_total 629
telemt_me_reconnect_attempts_total 71325
telemt_me_reconnect_success_total 22132
telemt_me_reader_eof_total 24343
telemt_me_idle_close_by_peer_total 24343
telemt_me_route_drop_no_conn_total 54479
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120434
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 23842
telemt_me_refill_failed_total 1535
telemt_me_writer_restored_same_endpoint_total 22117
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1710
telemt_user_connections_total{user="hello"} 136929
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 1418719500 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 44049148163 (41.02 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 83189.8 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 175252
telemt_connections_bad_total 1912
telemt_handshake_timeouts_total 2862
telemt_upstream_connect_attempt_total 22782
telemt_upstream_connect_success_total 22780
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10501
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 19750
telemt_me_reconnect_success_total 18577
telemt_me_reader_eof_total 19916
telemt_me_idle_close_by_peer_total 19916
telemt_me_route_drop_no_conn_total 67504
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163969
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 76
telemt_me_writer_removed_unexpected_total 18777
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18557
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 163896
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 2965904280 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 73111413544 (68.09 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 83165.4 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252724
telemt_connections_bad_total 13611
telemt_handshake_timeouts_total 1922
telemt_upstream_connect_attempt_total 35265
telemt_upstream_connect_success_total 25335
telemt_upstream_connect_fail_total 9930
telemt_upstream_connect_attempts_per_request{bucket="1"} 35265
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12727
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12424
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9930
telemt_me_keepalive_timeout_total 3350
telemt_me_reconnect_attempts_total 69851
telemt_me_reconnect_success_total 18314
telemt_me_reader_eof_total 20490
telemt_me_idle_close_by_peer_total 20483
telemt_me_route_drop_no_conn_total 91515
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212964
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 643
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 456
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 20156
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18304
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1842
telemt_user_connections_total{user="hello"} 215696
telemt_user_connections_current{user="hello"} 205
telemt_user_octets_from_client{user="hello"} 4311504210 (4.02 GB)
telemt_user_octets_to_client{user="hello"} 83250439909 (77.53 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 33336.9 (9h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38687
telemt_connections_bad_total 6901
telemt_handshake_timeouts_total 165
telemt_upstream_connect_attempt_total 11450
telemt_upstream_connect_success_total 11339
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 11450
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6377
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 275
telemt_me_reconnect_attempts_total 10641
telemt_me_reconnect_success_total 9675
telemt_me_reader_eof_total 10314
telemt_me_idle_close_by_peer_total 10314
telemt_me_route_drop_no_conn_total 10717
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30625
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 9791
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9657
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 30625
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 231085676 (220.38 MB)
telemt_user_octets_to_client{user="hello"} 10219352092 (9.52 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 83121.7 (23h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 426624
telemt_connections_bad_total 8064
telemt_handshake_timeouts_total 3235
telemt_upstream_connect_attempt_total 17727
telemt_upstream_connect_success_total 17630
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 17727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8212
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 1456
telemt_me_reconnect_attempts_total 17124
telemt_me_reconnect_success_total 13490
telemt_me_reader_eof_total 14489
telemt_me_idle_close_by_peer_total 14486
telemt_me_route_drop_no_conn_total 189162
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 413334
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 361
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 13772
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13483
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 401569
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 6521351920 (6.07 GB)
telemt_user_octets_to_client{user="hello"} 233810916032 (217.75 GB)
telemt_user_unique_ips_current{user="hello"} 147
telemt_user_unique_ips_recent_window{user="hello"} 49
```