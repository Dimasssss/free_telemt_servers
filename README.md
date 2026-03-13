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

# Server Metrics 2026-03-13 18:28:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 125737.8 (34h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 531590
telemt_connections_bad_total 10241
telemt_handshake_timeouts_total 12178
telemt_upstream_connect_attempt_total 31575
telemt_upstream_connect_success_total 31420
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 31575
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3484
telemt_me_reconnect_attempts_total 29777
telemt_me_reconnect_success_total 25135
telemt_me_reader_eof_total 26846
telemt_me_idle_close_by_peer_total 26845
telemt_me_route_drop_no_conn_total 173760
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 460996
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1471
telemt_desync_full_logged_total 510
telemt_desync_suppressed_total 961
telemt_desync_frames_bucket_total{bucket="1_2"} 323
telemt_desync_frames_bucket_total{bucket="3_10"} 541
telemt_desync_frames_bucket_total{bucket="gt_10"} 607
telemt_pool_swap_total 112
telemt_me_writer_removed_unexpected_total 25560
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 25119
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 425
telemt_user_connections_total{user="hello"} 460565
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 8463948656 (7.88 GB)
telemt_user_octets_to_client{user="hello"} 218613992616 (203.60 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 125631.4 (34h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263402
telemt_connections_bad_total 1954
telemt_handshake_timeouts_total 1840
telemt_upstream_connect_attempt_total 116029
telemt_upstream_connect_success_total 115171
telemt_upstream_connect_fail_total 858
telemt_upstream_connect_attempts_per_request{bucket="1"} 116029
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 86583
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26859
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1729
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 858
telemt_me_keepalive_timeout_total 1532
telemt_me_reconnect_attempts_total 130080
telemt_me_reconnect_success_total 26033
telemt_me_reader_eof_total 30038
telemt_me_idle_close_by_peer_total 30038
telemt_me_route_drop_no_conn_total 83043
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 166881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 31
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
telemt_me_writer_removed_unexpected_total 29508
telemt_me_refill_failed_total 3247
telemt_me_writer_restored_same_endpoint_total 26016
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 3475
telemt_user_connections_total{user="hello"} 249536
telemt_user_connections_current{user="hello"} 194
telemt_user_octets_from_client{user="hello"} 2605326151 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 76508826625 (71.25 GB)
telemt_user_msgs_from_client{user="hello"} 1312340
telemt_user_msgs_to_client{user="hello"} 7537593
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 125595.2 (34h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 311265
telemt_connections_bad_total 2629
telemt_handshake_timeouts_total 19455
telemt_upstream_connect_attempt_total 33459
telemt_upstream_connect_success_total 33454
telemt_upstream_connect_fail_total 5
telemt_upstream_connect_attempts_per_request{bucket="1"} 33459
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17917
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 5
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2705
telemt_me_reconnect_attempts_total 28369
telemt_me_reconnect_success_total 27137
telemt_me_reader_eof_total 29104
telemt_me_idle_close_by_peer_total 29104
telemt_me_route_drop_no_conn_total 110841
telemt_me_route_drop_channel_closed_total 17
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278247
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 56
telemt_desync_frames_bucket_total{bucket="1_2"} 9
telemt_desync_frames_bucket_total{bucket="3_10"} 34
telemt_desync_frames_bucket_total{bucket="gt_10"} 61
telemt_pool_swap_total 115
telemt_me_writer_removed_unexpected_total 27441
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 27117
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 304
telemt_user_connections_total{user="hello"} 278155
telemt_user_connections_current{user="hello"} 185
telemt_user_octets_from_client{user="hello"} 10317087532 (9.61 GB)
telemt_user_octets_to_client{user="hello"} 114455392804 (106.59 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 125570.5 (34h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 416501
telemt_connections_bad_total 15137
telemt_handshake_timeouts_total 3887
telemt_upstream_connect_attempt_total 60861
telemt_upstream_connect_success_total 50601
telemt_upstream_connect_fail_total 10260
telemt_upstream_connect_attempts_per_request{bucket="1"} 60861
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18275
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10260
telemt_me_keepalive_timeout_total 4678
telemt_me_reconnect_attempts_total 114953
telemt_me_reconnect_success_total 25295
telemt_me_reader_eof_total 28830
telemt_me_idle_close_by_peer_total 28823
telemt_me_route_drop_no_conn_total 143594
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 348406
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1361
telemt_desync_full_logged_total 406
telemt_desync_suppressed_total 955
telemt_desync_frames_bucket_total{bucket="1_2"} 335
telemt_desync_frames_bucket_total{bucket="3_10"} 524
telemt_desync_frames_bucket_total{bucket="gt_10"} 502
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 28421
telemt_me_refill_failed_total 2796
telemt_me_writer_restored_same_endpoint_total 25285
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3126
telemt_user_connections_total{user="hello"} 367287
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 8403419075 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 130732867936 (121.75 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 75742.1 (21h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126204
telemt_connections_bad_total 15675
telemt_handshake_timeouts_total 1406
telemt_upstream_connect_attempt_total 29616
telemt_upstream_connect_success_total 29338
telemt_upstream_connect_fail_total 278
telemt_upstream_connect_attempts_per_request{bucket="1"} 29616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15159
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 93
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 278
telemt_me_keepalive_timeout_total 1200
telemt_me_reconnect_attempts_total 34018
telemt_me_reconnect_success_total 20628
telemt_me_reader_eof_total 22120
telemt_me_idle_close_by_peer_total 22120
telemt_me_route_drop_no_conn_total 39475
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 100136
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 493
telemt_desync_full_logged_total 109
telemt_desync_suppressed_total 384
telemt_desync_frames_bucket_total{bucket="1_2"} 72
telemt_desync_frames_bucket_total{bucket="3_10"} 261
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 21238
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 20610
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 610
telemt_user_connections_total{user="hello"} 105033
telemt_user_connections_current{user="hello"} 141
telemt_user_octets_from_client{user="hello"} 1223759441 (1.14 GB)
telemt_user_octets_to_client{user="hello"} 35170789911 (32.76 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 125527.5 (34h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768163
telemt_connections_bad_total 24767
telemt_handshake_timeouts_total 24617
telemt_upstream_connect_attempt_total 26052
telemt_upstream_connect_success_total 25914
telemt_upstream_connect_fail_total 138
telemt_upstream_connect_attempts_per_request{bucket="1"} 26052
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 138
telemt_me_keepalive_timeout_total 3003
telemt_me_reconnect_attempts_total 24321
telemt_me_reconnect_success_total 19678
telemt_me_reader_eof_total 21117
telemt_me_idle_close_by_peer_total 21114
telemt_me_route_drop_no_conn_total 365310
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 720740
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 689
telemt_desync_full_logged_total 224
telemt_desync_suppressed_total 465
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 116
telemt_me_writer_removed_unexpected_total 20082
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 19671
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 404
telemt_user_connections_total{user="hello"} 693612
telemt_user_connections_current{user="hello"} 438
telemt_user_octets_from_client{user="hello"} 12170203628 (11.33 GB)
telemt_user_octets_to_client{user="hello"} 343772624744 (320.16 GB)
telemt_user_unique_ips_current{user="hello"} 164
telemt_user_unique_ips_recent_window{user="hello"} 55
```