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

# Server Metrics 2026-03-16 10:32:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 130680.1 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 658622
telemt_connections_bad_total 20754
telemt_handshake_timeouts_total 22548
telemt_upstream_connect_attempt_total 30575
telemt_upstream_connect_success_total 30429
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 30575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13575
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16807
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 35174
telemt_me_reconnect_success_total 23926
telemt_me_reader_eof_total 25751
telemt_me_idle_close_by_peer_total 25751
telemt_me_route_drop_no_conn_total 591407
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636826
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2946
telemt_desync_full_logged_total 1138
telemt_desync_suppressed_total 1808
telemt_desync_frames_bucket_total{bucket="1_2"} 649
telemt_desync_frames_bucket_total{bucket="3_10"} 1127
telemt_desync_frames_bucket_total{bucket="gt_10"} 1170
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24535
telemt_me_refill_failed_total 347
telemt_me_writer_restored_same_endpoint_total 23891
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 609
telemt_user_connections_total{user="hello"} 573375
telemt_user_connections_current{user="hello"} 579
telemt_user_octets_from_client{user="hello"} 11042619052 (10.28 GB)
telemt_user_octets_to_client{user="hello"} 346883805432 (323.06 GB)
telemt_user_unique_ips_current{user="hello"} 184
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 130688.0 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269603
telemt_connections_bad_total 3798
telemt_handshake_timeouts_total 15695
telemt_upstream_connect_attempt_total 34976
telemt_upstream_connect_success_total 34901
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 34976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19120
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 718
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 38309
telemt_me_reconnect_success_total 27982
telemt_me_reader_eof_total 30018
telemt_me_idle_close_by_peer_total 30017
telemt_me_route_drop_no_conn_total 127429
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 240830
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 199
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 133
telemt_desync_frames_bucket_total{bucket="1_2"} 40
telemt_desync_frames_bucket_total{bucket="3_10"} 71
telemt_desync_frames_bucket_total{bucket="gt_10"} 88
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 28699
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 27966
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 717
telemt_user_connections_total{user="hello"} 240362
telemt_user_connections_current{user="hello"} 372
telemt_user_octets_from_client{user="hello"} 5109325405 (4.76 GB)
telemt_user_octets_to_client{user="hello"} 127440148444 (118.69 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 95
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 130680.1 (36h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 274747
telemt_connections_bad_total 5770
telemt_handshake_timeouts_total 6644
telemt_upstream_connect_attempt_total 36432
telemt_upstream_connect_success_total 36424
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 36432
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15769
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20601
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 37271
telemt_me_reconnect_success_total 29844
telemt_me_reader_eof_total 32076
telemt_me_idle_close_by_peer_total 32075
telemt_me_route_drop_no_conn_total 95138
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223257
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 44
telemt_desync_suppressed_total 69
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 30371
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 29836
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 527
telemt_user_connections_total{user="hello"} 222944
telemt_user_connections_current{user="hello"} 244
telemt_user_octets_from_client{user="hello"} 17743223325 (16.52 GB)
telemt_user_octets_to_client{user="hello"} 122573567836 (114.16 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 81
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 130679.7 (36h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402547
telemt_connections_bad_total 1415
telemt_handshake_timeouts_total 3765
telemt_upstream_connect_attempt_total 30139
telemt_upstream_connect_success_total 30098
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 30139
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14518
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15408
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 28572
telemt_me_reconnect_success_total 23580
telemt_me_reader_eof_total 25289
telemt_me_idle_close_by_peer_total 25288
telemt_me_route_drop_no_conn_total 139928
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372966
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1360
telemt_desync_full_logged_total 457
telemt_desync_suppressed_total 903
telemt_desync_frames_bucket_total{bucket="1_2"} 279
telemt_desync_frames_bucket_total{bucket="3_10"} 575
telemt_desync_frames_bucket_total{bucket="gt_10"} 506
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 24049
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 23569
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 372837
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 6115918658 (5.70 GB)
telemt_user_octets_to_client{user="hello"} 146539445228 (136.48 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 105751.0 (29h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 252610
telemt_connections_bad_total 42317
telemt_handshake_timeouts_total 4321
telemt_upstream_connect_attempt_total 30087
telemt_upstream_connect_success_total 29922
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 30087
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13257
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16513
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 119000
telemt_me_reconnect_success_total 24492
telemt_me_reader_eof_total 26019
telemt_me_idle_close_by_peer_total 26019
telemt_me_route_drop_no_conn_total 77947
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198732
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 663
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 508
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 267
telemt_desync_frames_bucket_total{bucket="gt_10"} 299
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24700
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 24388
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 198345
telemt_user_connections_current{user="hello"} 140
telemt_user_octets_from_client{user="hello"} 2552338949 (2.38 GB)
telemt_user_octets_to_client{user="hello"} 88839938843 (82.74 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 59
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 130679.2 (36h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 901660
telemt_connections_bad_total 73086
telemt_handshake_timeouts_total 10533
telemt_upstream_connect_attempt_total 27431
telemt_upstream_connect_success_total 27285
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 27431
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12953
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14289
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 23365
telemt_me_reconnect_success_total 20757
telemt_me_reader_eof_total 22173
telemt_me_idle_close_by_peer_total 22173
telemt_me_route_drop_no_conn_total 680053
telemt_me_route_drop_channel_closed_total 123
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 887699
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 444
telemt_desync_full_logged_total 129
telemt_desync_suppressed_total 315
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 138
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 21085
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 20730
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 746316
telemt_user_connections_current{user="hello"} 760
telemt_user_octets_from_client{user="hello"} 15786404308 (14.70 GB)
telemt_user_octets_to_client{user="hello"} 440836912228 (410.56 GB)
telemt_user_unique_ips_current{user="hello"} 269
telemt_user_unique_ips_recent_window{user="hello"} 133
```