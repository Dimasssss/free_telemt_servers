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

# Server Metrics 2026-03-13 18:59:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 127571.6 (35h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 540803
telemt_connections_bad_total 11658
telemt_handshake_timeouts_total 12315
telemt_upstream_connect_attempt_total 32350
telemt_upstream_connect_success_total 32185
telemt_upstream_connect_fail_total 165
telemt_upstream_connect_attempts_per_request{bucket="1"} 32350
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17222
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 165
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 5038
telemt_me_reconnect_attempts_total 30077
telemt_me_reconnect_success_total 25429
telemt_me_reader_eof_total 27158
telemt_me_idle_close_by_peer_total 27157
telemt_me_route_drop_no_conn_total 177468
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 467899
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1495
telemt_desync_full_logged_total 515
telemt_desync_suppressed_total 980
telemt_desync_frames_bucket_total{bucket="1_2"} 327
telemt_desync_frames_bucket_total{bucket="3_10"} 548
telemt_desync_frames_bucket_total{bucket="gt_10"} 620
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 25859
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25413
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 430
telemt_user_connections_total{user="hello"} 467843
telemt_user_connections_current{user="hello"} 313
telemt_user_octets_from_client{user="hello"} 8659017798 (8.06 GB)
telemt_user_octets_to_client{user="hello"} 221905435736 (206.67 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 86
telemt_user_unique_ips_recent_window{user="hello"} 33
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 127465.4 (35h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 269832
telemt_connections_bad_total 1957
telemt_handshake_timeouts_total 1861
telemt_upstream_connect_attempt_total 121786
telemt_upstream_connect_success_total 120870
telemt_upstream_connect_fail_total 916
telemt_upstream_connect_attempts_per_request{bucket="1"} 121786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 91458
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27453
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1959
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 916
telemt_me_keepalive_timeout_total 3574
telemt_me_reconnect_attempts_total 132392
telemt_me_reconnect_success_total 26112
telemt_me_reader_eof_total 30176
telemt_me_idle_close_by_peer_total 30176
telemt_me_route_drop_no_conn_total 83162
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 167517
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 32
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
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 29674
telemt_me_refill_failed_total 3316
telemt_me_writer_restored_same_endpoint_total 26095
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3562
telemt_user_connections_total{user="hello"} 255700
telemt_user_connections_current{user="hello"} 221
telemt_user_octets_from_client{user="hello"} 2636270378 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 77403625824 (72.09 GB)
telemt_user_msgs_from_client{user="hello"} 1381772
telemt_user_msgs_to_client{user="hello"} 7818318
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 127429.0 (35h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316926
telemt_connections_bad_total 2630
telemt_handshake_timeouts_total 20653
telemt_upstream_connect_attempt_total 33910
telemt_upstream_connect_success_total 33905
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 33910
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15700
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2748
telemt_me_reconnect_attempts_total 28733
telemt_me_reconnect_success_total 27498
telemt_me_reader_eof_total 29495
telemt_me_idle_close_by_peer_total 29495
telemt_me_route_drop_no_conn_total 113098
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 282557
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
telemt_pool_swap_total 117
telemt_me_writer_removed_unexpected_total 27808
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27478
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 310
telemt_user_connections_total{user="hello"} 282466
telemt_user_connections_current{user="hello"} 154
telemt_user_octets_from_client{user="hello"} 10393684928 (9.68 GB)
telemt_user_octets_to_client{user="hello"} 118008882308 (109.90 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 127404.7 (35h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 421648
telemt_connections_bad_total 15145
telemt_handshake_timeouts_total 3893
telemt_upstream_connect_attempt_total 61586
telemt_upstream_connect_success_total 51312
telemt_upstream_connect_fail_total 10274
telemt_upstream_connect_attempts_per_request{bucket="1"} 61586
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32328
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18682
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 293
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10274
telemt_me_keepalive_timeout_total 4705
telemt_me_reconnect_attempts_total 116537
telemt_me_reconnect_success_total 25916
telemt_me_reader_eof_total 29486
telemt_me_idle_close_by_peer_total 29479
telemt_me_route_drop_no_conn_total 145758
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 353344
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1388
telemt_desync_full_logged_total 418
telemt_desync_suppressed_total 970
telemt_desync_frames_bucket_total{bucket="1_2"} 346
telemt_desync_frames_bucket_total{bucket="3_10"} 529
telemt_desync_frames_bucket_total{bucket="gt_10"} 513
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 29079
telemt_me_refill_failed_total 2826
telemt_me_writer_restored_same_endpoint_total 25906
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3163
telemt_user_connections_total{user="hello"} 372225
telemt_user_connections_current{user="hello"} 168
telemt_user_octets_from_client{user="hello"} 8436331479 (7.86 GB)
telemt_user_octets_to_client{user="hello"} 132356816980 (123.27 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 77576.2 (21h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 130220
telemt_connections_bad_total 16001
telemt_handshake_timeouts_total 1413
telemt_upstream_connect_attempt_total 30025
telemt_upstream_connect_success_total 29742
telemt_upstream_connect_fail_total 283
telemt_upstream_connect_attempts_per_request{bucket="1"} 30025
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14278
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 283
telemt_me_keepalive_timeout_total 1218
telemt_me_reconnect_attempts_total 34333
telemt_me_reconnect_success_total 20943
telemt_me_reader_eof_total 22452
telemt_me_idle_close_by_peer_total 22452
telemt_me_route_drop_no_conn_total 40716
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103659
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 557
telemt_desync_full_logged_total 127
telemt_desync_suppressed_total 430
telemt_desync_frames_bucket_total{bucket="1_2"} 78
telemt_desync_frames_bucket_total{bucket="3_10"} 281
telemt_desync_frames_bucket_total{bucket="gt_10"} 198
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 21555
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20925
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 612
telemt_user_connections_total{user="hello"} 108554
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 1251156445 (1.17 GB)
telemt_user_octets_to_client{user="hello"} 38162279563 (35.54 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 127360.9 (35h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 780133
telemt_connections_bad_total 24786
telemt_handshake_timeouts_total 24819
telemt_upstream_connect_attempt_total 26351
telemt_upstream_connect_success_total 26212
telemt_upstream_connect_fail_total 139
telemt_upstream_connect_attempts_per_request{bucket="1"} 26351
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13924
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 139
telemt_me_keepalive_timeout_total 3031
telemt_me_reconnect_attempts_total 24533
telemt_me_reconnect_success_total 19889
telemt_me_reader_eof_total 21343
telemt_me_idle_close_by_peer_total 21340
telemt_me_route_drop_no_conn_total 370840
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 731602
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 691
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 466
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 226
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 118
telemt_me_writer_removed_unexpected_total 20297
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19882
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 408
telemt_user_connections_total{user="hello"} 704470
telemt_user_connections_current{user="hello"} 405
telemt_user_octets_from_client{user="hello"} 12267192080 (11.42 GB)
telemt_user_octets_to_client{user="hello"} 347712006420 (323.83 GB)
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 58
```