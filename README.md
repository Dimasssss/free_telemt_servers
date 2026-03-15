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

# Server Metrics 2026-03-15 12:40:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 51966.4 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 227957
telemt_connections_bad_total 1867
telemt_handshake_timeouts_total 4741
telemt_upstream_connect_attempt_total 13163
telemt_upstream_connect_success_total 13093
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13163
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7262
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13868
telemt_me_reconnect_success_total 10496
telemt_me_reader_eof_total 11217
telemt_me_idle_close_by_peer_total 11217
telemt_me_route_drop_no_conn_total 427030
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273688
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1568
telemt_desync_full_logged_total 625
telemt_desync_suppressed_total 943
telemt_desync_frames_bucket_total{bucket="1_2"} 261
telemt_desync_frames_bucket_total{bucket="3_10"} 629
telemt_desync_frames_bucket_total{bucket="gt_10"} 678
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 10708
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10465
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 212
telemt_user_connections_total{user="hello"} 212799
telemt_user_connections_current{user="hello"} 399
telemt_user_octets_from_client{user="hello"} 4242400752 (3.95 GB)
telemt_user_octets_to_client{user="hello"} 196078356080 (182.61 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 51972.8 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 81492
telemt_connections_bad_total 2693
telemt_handshake_timeouts_total 6662
telemt_upstream_connect_attempt_total 14288
telemt_upstream_connect_success_total 14288
telemt_upstream_connect_attempts_per_request{bucket="1"} 14288
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6126
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8047
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14001
telemt_me_reconnect_success_total 11663
telemt_me_reader_eof_total 12470
telemt_me_idle_close_by_peer_total 12470
telemt_me_route_drop_no_conn_total 35917
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69601
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11860
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11647
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 69599
telemt_user_connections_current{user="hello"} 229
telemt_user_octets_from_client{user="hello"} 1420333000 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 33250238160 (30.97 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 51965.4 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 84533
telemt_connections_bad_total 1034
telemt_handshake_timeouts_total 2638
telemt_upstream_connect_attempt_total 15170
telemt_upstream_connect_success_total 15162
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6588
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8544
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 14682
telemt_me_reconnect_success_total 12537
telemt_me_reader_eof_total 13419
telemt_me_idle_close_by_peer_total 13419
telemt_me_route_drop_no_conn_total 32610
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77167
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 51
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 33
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 24
telemt_desync_frames_bucket_total{bucket="gt_10"} 23
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 12723
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12529
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 186
telemt_user_connections_total{user="hello"} 77081
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 9569747364 (8.91 GB)
telemt_user_octets_to_client{user="hello"} 46129606512 (42.96 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 51965.1 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 115453
telemt_connections_bad_total 395
telemt_handshake_timeouts_total 747
telemt_upstream_connect_attempt_total 12192
telemt_upstream_connect_success_total 12191
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12192
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9651
telemt_me_reconnect_success_total 9597
telemt_me_reader_eof_total 10241
telemt_me_idle_close_by_peer_total 10241
telemt_me_route_drop_no_conn_total 45901
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 105347
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 288
telemt_desync_full_logged_total 87
telemt_desync_suppressed_total 201
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 118
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 9705
telemt_me_writer_restored_same_endpoint_total 9586
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 105267
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 1884227688 (1.75 GB)
telemt_user_octets_to_client{user="hello"} 56868750636 (52.96 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 27036.5 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62161
telemt_connections_bad_total 15985
telemt_handshake_timeouts_total 875
telemt_upstream_connect_attempt_total 8629
telemt_upstream_connect_success_total 8569
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3850
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4685
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_reconnect_attempts_total 101464
telemt_me_reconnect_success_total 7044
telemt_me_reader_eof_total 7345
telemt_me_idle_close_by_peer_total 7345
telemt_me_route_drop_no_conn_total 21690
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 43874
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 113
telemt_desync_full_logged_total 24
telemt_desync_suppressed_total 89
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 50
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 7037
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6940
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 44010
telemt_user_connections_current{user="hello"} 81
telemt_user_octets_from_client{user="hello"} 667846809 (636.91 MB)
telemt_user_octets_to_client{user="hello"} 17369003731 (16.18 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 51964.6 (14h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 300447
telemt_connections_bad_total 47763
telemt_handshake_timeouts_total 2328
telemt_upstream_connect_attempt_total 11006
telemt_upstream_connect_success_total 10939
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 11006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5469
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5467
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 8390
telemt_me_reconnect_success_total 8334
telemt_me_reader_eof_total 8873
telemt_me_idle_close_by_peer_total 8873
telemt_me_route_drop_no_conn_total 133903
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 241437
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 186
telemt_desync_full_logged_total 65
telemt_desync_suppressed_total 121
telemt_desync_frames_bucket_total{bucket="1_2"} 80
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8407
telemt_me_writer_restored_same_endpoint_total 8307
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 239799
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 5036556944 (4.69 GB)
telemt_user_octets_to_client{user="hello"} 115937460940 (107.98 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 69
```