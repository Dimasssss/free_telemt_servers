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

# Server Metrics 2026-03-13 23:19:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 143153.4 (39h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 583301
telemt_connections_bad_total 18927
telemt_handshake_timeouts_total 12830
telemt_upstream_connect_attempt_total 36388
telemt_upstream_connect_success_total 36205
telemt_upstream_connect_fail_total 183
telemt_upstream_connect_attempts_per_request{bucket="1"} 36388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19498
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 183
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5156
telemt_me_reconnect_attempts_total 33334
telemt_me_reconnect_success_total 28671
telemt_me_reader_eof_total 30624
telemt_me_idle_close_by_peer_total 30623
telemt_me_route_drop_no_conn_total 192121
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 500893
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1620
telemt_desync_full_logged_total 551
telemt_desync_suppressed_total 1069
telemt_desync_frames_bucket_total{bucket="1_2"} 349
telemt_desync_frames_bucket_total{bucket="3_10"} 607
telemt_desync_frames_bucket_total{bucket="gt_10"} 664
telemt_pool_swap_total 128
telemt_me_writer_removed_unexpected_total 29137
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 28655
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 466
telemt_user_connections_total{user="hello"} 500787
telemt_user_connections_current{user="hello"} 172
telemt_user_octets_from_client{user="hello"} 15318341294 (14.27 GB)
telemt_user_octets_to_client{user="hello"} 248538766072 (231.47 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 51
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 143046.3 (39h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 297908
telemt_connections_bad_total 2157
telemt_handshake_timeouts_total 1921
telemt_upstream_connect_attempt_total 140622
telemt_upstream_connect_success_total 139576
telemt_upstream_connect_fail_total 1046
telemt_upstream_connect_attempts_per_request{bucket="1"} 140622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 106172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30989
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2415
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1046
telemt_me_keepalive_timeout_total 3729
telemt_me_reconnect_attempts_total 149837
telemt_me_reconnect_success_total 29137
telemt_me_reader_eof_total 33686
telemt_me_idle_close_by_peer_total 33686
telemt_me_route_drop_no_conn_total 91271
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 179418
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 36
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
telemt_me_writer_removed_unexpected_total 33181
telemt_me_refill_failed_total 3766
telemt_me_writer_restored_same_endpoint_total 29120
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4044
telemt_user_connections_total{user="hello"} 282530
telemt_user_connections_current{user="hello"} 101
telemt_user_octets_from_client{user="hello"} 2975049227 (2.77 GB)
telemt_user_octets_to_client{user="hello"} 88936411783 (82.83 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 143013.6 (39h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 348485
telemt_connections_bad_total 2701
telemt_handshake_timeouts_total 30670
telemt_upstream_connect_attempt_total 37977
telemt_upstream_connect_success_total 37971
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 37977
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17442
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20482
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 2888
telemt_me_reconnect_attempts_total 32061
telemt_me_reconnect_success_total 30810
telemt_me_reader_eof_total 33073
telemt_me_idle_close_by_peer_total 33073
telemt_me_route_drop_no_conn_total 123464
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 302904
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
telemt_pool_swap_total 132
telemt_me_writer_removed_unexpected_total 31163
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 30790
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 353
telemt_user_connections_total{user="hello"} 302807
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 12462423024 (11.61 GB)
telemt_user_octets_to_client{user="hello"} 126000138100 (117.35 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 142985.6 (39h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 450558
telemt_connections_bad_total 15326
telemt_handshake_timeouts_total 4250
telemt_upstream_connect_attempt_total 65565
telemt_upstream_connect_success_total 55174
telemt_upstream_connect_fail_total 10391
telemt_upstream_connect_attempts_per_request{bucket="1"} 65565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20718
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 314
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10391
telemt_me_keepalive_timeout_total 5020
telemt_me_reconnect_attempts_total 131497
telemt_me_reconnect_success_total 29022
telemt_me_reader_eof_total 33061
telemt_me_idle_close_by_peer_total 33054
telemt_me_route_drop_no_conn_total 157868
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 380890
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1663
telemt_desync_full_logged_total 487
telemt_desync_suppressed_total 1176
telemt_desync_frames_bucket_total{bucket="1_2"} 387
telemt_desync_frames_bucket_total{bucket="3_10"} 635
telemt_desync_frames_bucket_total{bucket="gt_10"} 641
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 32585
telemt_me_refill_failed_total 3196
telemt_me_writer_restored_same_endpoint_total 29012
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3563
telemt_user_connections_total{user="hello"} 399732
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 9013168803 (8.39 GB)
telemt_user_octets_to_client{user="hello"} 152485318484 (142.01 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 93157.3 (25h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 155948
telemt_connections_bad_total 23078
telemt_handshake_timeouts_total 1543
telemt_upstream_connect_attempt_total 34426
telemt_upstream_connect_success_total 34105
telemt_upstream_connect_fail_total 321
telemt_upstream_connect_attempts_per_request{bucket="1"} 34426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17495
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16494
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 116
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 321
telemt_me_keepalive_timeout_total 1326
telemt_me_reconnect_attempts_total 37962
telemt_me_reconnect_success_total 24556
telemt_me_reader_eof_total 26278
telemt_me_idle_close_by_peer_total 26278
telemt_me_route_drop_no_conn_total 47280
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 121678
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
telemt_pool_swap_total 66
telemt_me_writer_removed_unexpected_total 25209
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 24538
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 653
telemt_user_connections_total{user="hello"} 126546
telemt_user_connections_current{user="hello"} 46
telemt_user_octets_from_client{user="hello"} 1524910185 (1.42 GB)
telemt_user_octets_to_client{user="hello"} 60460658399 (56.31 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 4
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 142941.9 (39h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 854455
telemt_connections_bad_total 27235
telemt_handshake_timeouts_total 25154
telemt_upstream_connect_attempt_total 29438
telemt_upstream_connect_success_total 29283
telemt_upstream_connect_fail_total 155
telemt_upstream_connect_attempts_per_request{bucket="1"} 29438
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13657
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15585
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 155
telemt_me_keepalive_timeout_total 3395
telemt_me_reconnect_attempts_total 26865
telemt_me_reconnect_success_total 22205
telemt_me_reader_eof_total 23805
telemt_me_idle_close_by_peer_total 23802
telemt_me_route_drop_no_conn_total 407141
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 797836
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 697
telemt_desync_full_logged_total 227
telemt_desync_suppressed_total 470
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 229
telemt_desync_frames_bucket_total{bucket="gt_10"} 219
telemt_pool_swap_total 133
telemt_me_writer_removed_unexpected_total 22642
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 22198
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 437
telemt_user_connections_total{user="hello"} 770690
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 13254636740 (12.34 GB)
telemt_user_octets_to_client{user="hello"} 392265090808 (365.33 GB)
telemt_user_unique_ips_current{user="hello"} 102
telemt_user_unique_ips_recent_window{user="hello"} 33
```