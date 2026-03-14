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

# Server Metrics 2026-03-14 07:07:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 171266.5 (47h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 656992
telemt_connections_bad_total 32378
telemt_handshake_timeouts_total 13059
telemt_upstream_connect_attempt_total 43597
telemt_upstream_connect_success_total 43377
telemt_upstream_connect_fail_total 220
telemt_upstream_connect_attempts_per_request{bucket="1"} 43597
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19825
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23400
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 220
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5680
telemt_me_reconnect_attempts_total 39141
telemt_me_reconnect_success_total 34449
telemt_me_reader_eof_total 36833
telemt_me_idle_close_by_peer_total 36832
telemt_me_route_drop_no_conn_total 216949
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 558731
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2082
telemt_desync_full_logged_total 712
telemt_desync_suppressed_total 1370
telemt_desync_frames_bucket_total{bucket="1_2"} 450
telemt_desync_frames_bucket_total{bucket="3_10"} 765
telemt_desync_frames_bucket_total{bucket="gt_10"} 867
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 34966
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34429
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 517
telemt_user_connections_total{user="hello"} 558615
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 16333799434 (15.21 GB)
telemt_user_octets_to_client{user="hello"} 269173006796 (250.69 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 171159.9 (47h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 331215
telemt_connections_bad_total 2324
telemt_handshake_timeouts_total 2526
telemt_upstream_connect_attempt_total 150379
telemt_upstream_connect_success_total 149110
telemt_upstream_connect_fail_total 1269
telemt_upstream_connect_attempts_per_request{bucket="1"} 150379
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109930
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36756
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2424
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1269
telemt_me_keepalive_timeout_total 4014
telemt_me_reconnect_attempts_total 177852
telemt_me_reconnect_success_total 37262
telemt_me_reader_eof_total 42642
telemt_me_idle_close_by_peer_total 42642
telemt_me_route_drop_no_conn_total 108934
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 210482
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
telemt_me_writer_removed_unexpected_total 42002
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 37245
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4740
telemt_user_connections_total{user="hello"} 313590
telemt_user_connections_current{user="hello"} 133
telemt_user_octets_from_client{user="hello"} 3261136327 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 102344527483 (95.32 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 40
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 171123.6 (47h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 386728
telemt_connections_bad_total 2971
telemt_handshake_timeouts_total 35137
telemt_upstream_connect_attempt_total 45122
telemt_upstream_connect_success_total 45113
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45122
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20631
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24414
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3483
telemt_me_reconnect_attempts_total 37816
telemt_me_reconnect_success_total 36530
telemt_me_reader_eof_total 39287
telemt_me_idle_close_by_peer_total 39287
telemt_me_route_drop_no_conn_total 139575
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335159
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
telemt_pool_swap_total 163
telemt_me_writer_removed_unexpected_total 36972
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36509
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 442
telemt_user_connections_total{user="hello"} 334931
telemt_user_connections_current{user="hello"} 198
telemt_user_octets_from_client{user="hello"} 13510732344 (12.58 GB)
telemt_user_octets_to_client{user="hello"} 132762174908 (123.64 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 171099.2 (47h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 488883
telemt_connections_bad_total 16239
telemt_handshake_timeouts_total 4525
telemt_upstream_connect_attempt_total 75561
telemt_upstream_connect_success_total 64980
telemt_upstream_connect_fail_total 10581
telemt_upstream_connect_attempts_per_request{bucket="1"} 75561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38335
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26293
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 343
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10581
telemt_me_keepalive_timeout_total 5403
telemt_me_reconnect_attempts_total 143475
telemt_me_reconnect_success_total 37414
telemt_me_reader_eof_total 41927
telemt_me_idle_close_by_peer_total 41919
telemt_me_route_drop_no_conn_total 176473
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 416111
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1774
telemt_desync_full_logged_total 529
telemt_desync_suppressed_total 1245
telemt_desync_frames_bucket_total{bucket="1_2"} 420
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 41154
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 37404
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3740
telemt_user_connections_total{user="hello"} 434957
telemt_user_connections_current{user="hello"} 169
telemt_user_octets_from_client{user="hello"} 9395284083 (8.75 GB)
telemt_user_octets_to_client{user="hello"} 178011784780 (165.79 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 121270.5 (33h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 197724
telemt_connections_bad_total 29275
telemt_handshake_timeouts_total 1736
telemt_upstream_connect_attempt_total 42804
telemt_upstream_connect_success_total 42398
telemt_upstream_connect_fail_total 406
telemt_upstream_connect_attempts_per_request{bucket="1"} 42804
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21013
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 406
telemt_me_keepalive_timeout_total 2525
telemt_me_reconnect_attempts_total 44916
telemt_me_reconnect_success_total 31485
telemt_me_reader_eof_total 33706
telemt_me_idle_close_by_peer_total 33706
telemt_me_route_drop_no_conn_total 58873
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156446
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 647
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 319
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 93
telemt_me_writer_removed_unexpected_total 32195
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31467
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 710
telemt_user_connections_total{user="hello"} 161195
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 2399827225 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 74663668735 (69.54 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 171055.1 (47h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 977602
telemt_connections_bad_total 36058
telemt_handshake_timeouts_total 26069
telemt_upstream_connect_attempt_total 35477
telemt_upstream_connect_success_total 35288
telemt_upstream_connect_fail_total 189
telemt_upstream_connect_attempts_per_request{bucket="1"} 35477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18657
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 189
telemt_me_keepalive_timeout_total 4720
telemt_me_reconnect_attempts_total 31509
telemt_me_reconnect_success_total 26830
telemt_me_reader_eof_total 28801
telemt_me_idle_close_by_peer_total 28798
telemt_me_route_drop_no_conn_total 461028
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 906788
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
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 27316
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26823
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 486
telemt_user_connections_total{user="hello"} 879434
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 15117922268 (14.08 GB)
telemt_user_octets_to_client{user="hello"} 444555108216 (414.02 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 51
```