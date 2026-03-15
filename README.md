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

# Server Metrics 2026-03-15 06:38:44 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 30256.3 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86540
telemt_connections_bad_total 451
telemt_handshake_timeouts_total 1667
telemt_upstream_connect_attempt_total 7393
telemt_upstream_connect_success_total 7350
telemt_upstream_connect_fail_total 43
telemt_upstream_connect_attempts_per_request{bucket="1"} 7393
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4008
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 43
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 5861
telemt_me_reconnect_success_total 5841
telemt_me_reader_eof_total 6257
telemt_me_idle_close_by_peer_total 6257
telemt_me_route_drop_no_conn_total 92909
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92188
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 708
telemt_desync_full_logged_total 309
telemt_desync_suppressed_total 399
telemt_desync_frames_bucket_total{bucket="1_2"} 122
telemt_desync_frames_bucket_total{bucket="3_10"} 297
telemt_desync_frames_bucket_total{bucket="gt_10"} 289
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5889
telemt_me_writer_restored_same_endpoint_total 5810
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 81059
telemt_user_connections_current{user="hello"} 328
telemt_user_octets_from_client{user="hello"} 1029384652 (981.70 MB)
telemt_user_octets_to_client{user="hello"} 48398688780 (45.07 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 30263.0 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 28982
telemt_connections_bad_total 134
telemt_handshake_timeouts_total 120
telemt_upstream_connect_attempt_total 8149
telemt_upstream_connect_success_total 8149
telemt_upstream_connect_attempts_per_request{bucket="1"} 8149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4565
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6655
telemt_me_reconnect_success_total 6628
telemt_me_reader_eof_total 7127
telemt_me_idle_close_by_peer_total 7127
telemt_me_route_drop_no_conn_total 14528
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 27557
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6691
telemt_me_writer_restored_same_endpoint_total 6612
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 27560
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 740562120 (706.26 MB)
telemt_user_octets_to_client{user="hello"} 10339090232 (9.63 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 30255.7 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 36926
telemt_connections_bad_total 455
telemt_handshake_timeouts_total 1773
telemt_upstream_connect_attempt_total 8053
telemt_upstream_connect_success_total 8052
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8053
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3542
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4504
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 6562
telemt_me_reconnect_success_total 6533
telemt_me_reader_eof_total 7065
telemt_me_idle_close_by_peer_total 7065
telemt_me_route_drop_no_conn_total 12797
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33457
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 6590
telemt_me_writer_restored_same_endpoint_total 6529
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 33404
telemt_user_connections_current{user="hello"} 92
telemt_user_octets_from_client{user="hello"} 8792726144 (8.19 GB)
telemt_user_octets_to_client{user="hello"} 17989098180 (16.75 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 30255.4 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 41375
telemt_connections_bad_total 129
telemt_handshake_timeouts_total 275
telemt_upstream_connect_attempt_total 7118
telemt_upstream_connect_success_total 7117
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 7118
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3313
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3783
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5633
telemt_me_reconnect_success_total 5612
telemt_me_reader_eof_total 6015
telemt_me_idle_close_by_peer_total 6015
telemt_me_route_drop_no_conn_total 17984
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37088
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 78
telemt_desync_full_logged_total 21
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 19
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 27
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 5671
telemt_me_writer_restored_same_endpoint_total 5601
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 37007
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 678060560 (646.65 MB)
telemt_user_octets_to_client{user="hello"} 24387241536 (22.71 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 5326.8 (1h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7748
telemt_connections_bad_total 1018
telemt_handshake_timeouts_total 151
telemt_upstream_connect_attempt_total 2212
telemt_upstream_connect_success_total 2183
telemt_upstream_connect_fail_total 29
telemt_upstream_connect_attempts_per_request{bucket="1"} 2212
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1230
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 29
telemt_me_reconnect_attempts_total 96140
telemt_me_reconnect_success_total 1748
telemt_me_reader_eof_total 1726
telemt_me_idle_close_by_peer_total 1726
telemt_me_route_drop_no_conn_total 2084
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6295
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 1675
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 1644
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 6440
telemt_user_connections_current{user="hello"} 43
telemt_user_octets_from_client{user="hello"} 36319585 (34.64 MB)
telemt_user_octets_to_client{user="hello"} 1915405047 (1.78 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 30254.6 (8h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 104003
telemt_connections_bad_total 2565
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 6640
telemt_upstream_connect_success_total 6603
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 6640
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3291
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_reconnect_attempts_total 5111
telemt_me_reconnect_success_total 5088
telemt_me_reader_eof_total 5419
telemt_me_idle_close_by_peer_total 5419
telemt_me_route_drop_no_conn_total 55742
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 98032
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 25
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 14
telemt_desync_frames_bucket_total{bucket="1_2"} 8
telemt_desync_frames_bucket_total{bucket="3_10"} 9
telemt_desync_frames_bucket_total{bucket="gt_10"} 8
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 5111
telemt_me_writer_restored_same_endpoint_total 5061
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 23
telemt_user_connections_total{user="hello"} 96589
telemt_user_connections_current{user="hello"} 341
telemt_user_octets_from_client{user="hello"} 2400186088 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 50029857868 (46.59 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 54
```