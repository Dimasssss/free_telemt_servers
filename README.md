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

# Server Metrics 2026-03-14 12:38:33 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 191112.7 (53h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 758236
telemt_connections_bad_total 36205
telemt_handshake_timeouts_total 14526
telemt_upstream_connect_attempt_total 48454
telemt_upstream_connect_success_total 48213
telemt_upstream_connect_fail_total 241
telemt_upstream_connect_attempts_per_request{bucket="1"} 48454
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22090
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25969
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 154
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 241
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 6341
telemt_me_reconnect_attempts_total 44069
telemt_me_reconnect_success_total 38300
telemt_me_reader_eof_total 40950
telemt_me_idle_close_by_peer_total 40949
telemt_me_route_drop_no_conn_total 248901
telemt_me_route_drop_channel_closed_total 41
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 650173
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2791
telemt_desync_full_logged_total 932
telemt_desync_suppressed_total 1859
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 1045
telemt_desync_frames_bucket_total{bucket="gt_10"} 1168
telemt_pool_swap_total 174
telemt_me_writer_removed_unexpected_total 38891
telemt_me_refill_failed_total 173
telemt_me_writer_restored_same_endpoint_total 38280
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 591
telemt_user_connections_total{user="hello"} 650079
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 17965597890 (16.73 GB)
telemt_user_octets_to_client{user="hello"} 310746876712 (289.41 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 107
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 191005.6 (53h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375102
telemt_connections_bad_total 2877
telemt_handshake_timeouts_total 3360
telemt_upstream_connect_attempt_total 158398
telemt_upstream_connect_success_total 156990
telemt_upstream_connect_fail_total 1408
telemt_upstream_connect_attempts_per_request{bucket="1"} 158398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 113948
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1408
telemt_me_keepalive_timeout_total 5721
telemt_me_reconnect_attempts_total 196980
telemt_me_reconnect_success_total 42348
telemt_me_reader_eof_total 48278
telemt_me_idle_close_by_peer_total 48278
telemt_me_route_drop_no_conn_total 129413
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248482
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 47
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
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 47587
telemt_me_refill_failed_total 4824
telemt_me_writer_restored_same_endpoint_total 42330
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 5239
telemt_user_connections_total{user="hello"} 353375
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 3582831675 (3.34 GB)
telemt_user_octets_to_client{user="hello"} 113521748214 (105.73 GB)
telemt_user_msgs_from_client{user="hello"} 1713995
telemt_user_msgs_to_client{user="hello"} 9567945
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 190968.7 (53h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 431602
telemt_connections_bad_total 3334
telemt_handshake_timeouts_total 36748
telemt_upstream_connect_attempt_total 51001
telemt_upstream_connect_success_total 50991
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 51000
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27459
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 72
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4341
telemt_me_reconnect_attempts_total 42675
telemt_me_reconnect_success_total 41351
telemt_me_reader_eof_total 44419
telemt_me_idle_close_by_peer_total 44419
telemt_me_route_drop_no_conn_total 158331
telemt_me_route_drop_channel_closed_total 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 376017
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 147
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 80
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 53
telemt_desync_frames_bucket_total{bucket="gt_10"} 79
telemt_pool_swap_total 177
telemt_me_writer_removed_unexpected_total 41848
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 41330
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 497
telemt_user_connections_total{user="hello"} 375751
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 16239090318 (15.12 GB)
telemt_user_octets_to_client{user="hello"} 165831014147 (154.44 GB)
telemt_user_msgs_from_client{user="hello"} 166
telemt_user_msgs_to_client{user="hello"} 712
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 190944.3 (53h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 550428
telemt_connections_bad_total 16783
telemt_handshake_timeouts_total 5343
telemt_upstream_connect_attempt_total 81433
telemt_upstream_connect_success_total 70705
telemt_upstream_connect_fail_total 10728
telemt_upstream_connect_attempts_per_request{bucket="1"} 81433
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41051
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29252
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 393
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10728
telemt_me_keepalive_timeout_total 5857
telemt_me_reconnect_attempts_total 159464
telemt_me_reconnect_success_total 42132
telemt_me_reader_eof_total 47130
telemt_me_idle_close_by_peer_total 47122
telemt_me_route_drop_no_conn_total 198935
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472350
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 38
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2200
telemt_desync_full_logged_total 646
telemt_desync_suppressed_total 1554
telemt_desync_frames_bucket_total{bucket="1_2"} 512
telemt_desync_frames_bucket_total{bucket="3_10"} 835
telemt_desync_frames_bucket_total{bucket="gt_10"} 853
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 46280
telemt_me_refill_failed_total 3658
telemt_me_writer_restored_same_endpoint_total 42122
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 4148
telemt_user_connections_total{user="hello"} 491210
telemt_user_connections_current{user="hello"} 206
telemt_user_octets_from_client{user="hello"} 10367296099 (9.66 GB)
telemt_user_octets_to_client{user="hello"} 202899068284 (188.96 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 141115.9 (39h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 240484
telemt_connections_bad_total 38641
telemt_handshake_timeouts_total 2200
telemt_upstream_connect_attempt_total 49656
telemt_upstream_connect_success_total 49153
telemt_upstream_connect_fail_total 503
telemt_upstream_connect_attempts_per_request{bucket="1"} 49656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 503
telemt_me_keepalive_timeout_total 3152
telemt_me_reconnect_attempts_total 56785
telemt_me_reconnect_success_total 37247
telemt_me_reader_eof_total 39880
telemt_me_idle_close_by_peer_total 39880
telemt_me_route_drop_no_conn_total 73335
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 188311
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 861
telemt_desync_full_logged_total 203
telemt_desync_suppressed_total 658
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 394
telemt_desync_frames_bucket_total{bucket="gt_10"} 322
telemt_pool_swap_total 102
telemt_me_writer_removed_unexpected_total 38206
telemt_me_refill_failed_total 606
telemt_me_writer_restored_same_endpoint_total 37229
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 959
telemt_user_connections_total{user="hello"} 193067
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 2785376369 (2.59 GB)
telemt_user_octets_to_client{user="hello"} 89027534783 (82.91 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 190900.6 (53h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1115555
telemt_connections_bad_total 37948
telemt_handshake_timeouts_total 27379
telemt_upstream_connect_attempt_total 39755
telemt_upstream_connect_success_total 39547
telemt_upstream_connect_fail_total 208
telemt_upstream_connect_attempts_per_request{bucket="1"} 39755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20761
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 208
telemt_me_keepalive_timeout_total 5237
telemt_me_reconnect_attempts_total 34779
telemt_me_reconnect_success_total 30082
telemt_me_reader_eof_total 32254
telemt_me_idle_close_by_peer_total 32251
telemt_me_route_drop_no_conn_total 525206
telemt_me_route_drop_channel_closed_total 36
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1034596
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 809
telemt_desync_full_logged_total 268
telemt_desync_suppressed_total 541
telemt_desync_frames_bucket_total{bucket="1_2"} 260
telemt_desync_frames_bucket_total{bucket="3_10"} 269
telemt_desync_frames_bucket_total{bucket="gt_10"} 280
telemt_pool_swap_total 179
telemt_me_writer_removed_unexpected_total 30611
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 30075
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 529
telemt_user_connections_total{user="hello"} 1007200
telemt_user_connections_current{user="hello"} 486
telemt_user_octets_from_client{user="hello"} 21566876960 (20.09 GB)
telemt_user_octets_to_client{user="hello"} 509436513452 (474.45 GB)
telemt_user_unique_ips_current{user="hello"} 183
telemt_user_unique_ips_recent_window{user="hello"} 88
```