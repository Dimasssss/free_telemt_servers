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

# Server Metrics 2026-03-16 10:42:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 131293.1 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 677106
telemt_connections_bad_total 32840
telemt_handshake_timeouts_total 22753
telemt_upstream_connect_attempt_total 30632
telemt_upstream_connect_success_total 30486
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 30632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13595
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16844
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 35455
telemt_me_reconnect_success_total 23982
telemt_me_reader_eof_total 25814
telemt_me_idle_close_by_peer_total 25814
telemt_me_route_drop_no_conn_total 592771
telemt_me_route_drop_channel_closed_total 88
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 642873
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2955
telemt_desync_full_logged_total 1145
telemt_desync_suppressed_total 1810
telemt_desync_frames_bucket_total{bucket="1_2"} 653
telemt_desync_frames_bucket_total{bucket="3_10"} 1130
telemt_desync_frames_bucket_total{bucket="gt_10"} 1172
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 24598
telemt_me_refill_failed_total 354
telemt_me_writer_restored_same_endpoint_total 23947
telemt_me_writer_restored_fallback_total 35
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 616
telemt_user_connections_total{user="hello"} 579419
telemt_user_connections_current{user="hello"} 569
telemt_user_octets_from_client{user="hello"} 11084250508 (10.32 GB)
telemt_user_octets_to_client{user="hello"} 348413409944 (324.49 GB)
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 76
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 131300.2 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 273060
telemt_connections_bad_total 3798
telemt_handshake_timeouts_total 15707
telemt_upstream_connect_attempt_total 35057
telemt_upstream_connect_success_total 34982
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 35057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 718
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 38390
telemt_me_reconnect_success_total 28062
telemt_me_reader_eof_total 30099
telemt_me_idle_close_by_peer_total 30098
telemt_me_route_drop_no_conn_total 128724
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 244202
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 206
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 139
telemt_desync_frames_bucket_total{bucket="1_2"} 41
telemt_desync_frames_bucket_total{bucket="3_10"} 76
telemt_desync_frames_bucket_total{bucket="gt_10"} 89
telemt_pool_swap_total 111
telemt_me_writer_removed_unexpected_total 28781
telemt_me_refill_failed_total 314
telemt_me_writer_restored_same_endpoint_total 28046
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 719
telemt_user_connections_total{user="hello"} 243732
telemt_user_connections_current{user="hello"} 422
telemt_user_octets_from_client{user="hello"} 5217464537 (4.86 GB)
telemt_user_octets_to_client{user="hello"} 128938458072 (120.08 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 131292.6 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 277131
telemt_connections_bad_total 5787
telemt_handshake_timeouts_total 6875
telemt_upstream_connect_attempt_total 36525
telemt_upstream_connect_success_total 36517
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 36525
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20665
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 55
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 45
telemt_me_reconnect_attempts_total 37364
telemt_me_reconnect_success_total 29937
telemt_me_reader_eof_total 32166
telemt_me_idle_close_by_peer_total 32165
telemt_me_route_drop_no_conn_total 95864
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 225292
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
telemt_me_writer_removed_unexpected_total 30466
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 29929
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 224955
telemt_user_connections_current{user="hello"} 241
telemt_user_octets_from_client{user="hello"} 17758496409 (16.54 GB)
telemt_user_octets_to_client{user="hello"} 124015922840 (115.50 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 82
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 131292.3 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 407987
telemt_connections_bad_total 1421
telemt_handshake_timeouts_total 3878
telemt_upstream_connect_attempt_total 30226
telemt_upstream_connect_success_total 30185
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 30226
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15466
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 16
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 28659
telemt_me_reconnect_success_total 23667
telemt_me_reader_eof_total 25378
telemt_me_idle_close_by_peer_total 25377
telemt_me_route_drop_no_conn_total 141554
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 378028
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1390
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 923
telemt_desync_frames_bucket_total{bucket="1_2"} 282
telemt_desync_frames_bucket_total{bucket="3_10"} 592
telemt_desync_frames_bucket_total{bucket="gt_10"} 516
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 24138
telemt_me_refill_failed_total 151
telemt_me_writer_restored_same_endpoint_total 23656
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 377897
telemt_user_connections_current{user="hello"} 377
telemt_user_octets_from_client{user="hello"} 6163291726 (5.74 GB)
telemt_user_octets_to_client{user="hello"} 147859496316 (137.70 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 54
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 106363.6 (29h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 255972
telemt_connections_bad_total 43511
telemt_handshake_timeouts_total 4342
telemt_upstream_connect_attempt_total 30224
telemt_upstream_connect_success_total 30059
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 30224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16596
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 119089
telemt_me_reconnect_success_total 24581
telemt_me_reader_eof_total 26108
telemt_me_idle_close_by_peer_total 26108
telemt_me_route_drop_no_conn_total 78685
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200585
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 668
telemt_desync_full_logged_total 157
telemt_desync_suppressed_total 511
telemt_desync_frames_bucket_total{bucket="1_2"} 97
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 302
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 24789
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 24477
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 208
telemt_user_connections_total{user="hello"} 200197
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 2573180433 (2.40 GB)
telemt_user_octets_to_client{user="hello"} 89220487111 (83.09 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 131291.7 (36h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 909720
telemt_connections_bad_total 73429
telemt_handshake_timeouts_total 10626
telemt_upstream_connect_attempt_total 27561
telemt_upstream_connect_success_total 27415
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 27561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14374
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 23495
telemt_me_reconnect_success_total 20887
telemt_me_reader_eof_total 22303
telemt_me_idle_close_by_peer_total 22303
telemt_me_route_drop_no_conn_total 682528
telemt_me_route_drop_channel_closed_total 124
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 894514
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 174
telemt_desync_frames_bucket_total{bucket="3_10"} 148
telemt_desync_frames_bucket_total{bucket="gt_10"} 136
telemt_pool_swap_total 121
telemt_me_writer_removed_unexpected_total 21215
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 20860
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 753139
telemt_user_connections_current{user="hello"} 717
telemt_user_octets_from_client{user="hello"} 15971559524 (14.87 GB)
telemt_user_octets_to_client{user="hello"} 443356527904 (412.91 GB)
telemt_user_unique_ips_current{user="hello"} 244
telemt_user_unique_ips_recent_window{user="hello"} 82
```