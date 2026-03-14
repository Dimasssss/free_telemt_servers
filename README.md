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

# Server Metrics 2026-03-14 04:24:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 161490.8 (44h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 626875
telemt_connections_bad_total 31604
telemt_handshake_timeouts_total 12949
telemt_upstream_connect_attempt_total 41308
telemt_upstream_connect_success_total 41099
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 41308
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18768
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 5549
telemt_me_reconnect_attempts_total 37340
telemt_me_reconnect_success_total 32656
telemt_me_reader_eof_total 34906
telemt_me_idle_close_by_peer_total 34905
telemt_me_route_drop_no_conn_total 203512
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 530556
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1826
telemt_desync_full_logged_total 617
telemt_desync_suppressed_total 1209
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 675
telemt_desync_frames_bucket_total{bucket="gt_10"} 763
telemt_pool_swap_total 148
telemt_me_writer_removed_unexpected_total 33159
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 32636
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 503
telemt_user_connections_total{user="hello"} 530445
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 15747593802 (14.67 GB)
telemt_user_octets_to_client{user="hello"} 257939353144 (240.22 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 76
telemt_user_unique_ips_recent_window{user="hello"} 21
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 161383.8 (44h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 316833
telemt_connections_bad_total 2269
telemt_handshake_timeouts_total 2329
telemt_upstream_connect_attempt_total 146976
telemt_upstream_connect_success_total 145787
telemt_upstream_connect_fail_total 1189
telemt_upstream_connect_attempts_per_request{bucket="1"} 146976
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 108647
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34723
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2417
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1189
telemt_me_keepalive_timeout_total 3869
telemt_me_reconnect_attempts_total 171230
telemt_me_reconnect_success_total 34422
telemt_me_reader_eof_total 39595
telemt_me_idle_close_by_peer_total 39595
telemt_me_route_drop_no_conn_total 100519
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 196919
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 41
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
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 39026
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 34405
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 4604
telemt_user_connections_total{user="hello"} 300030
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 3133850519 (2.92 GB)
telemt_user_octets_to_client{user="hello"} 97007544283 (90.35 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 161347.6 (44h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 369343
telemt_connections_bad_total 2924
telemt_handshake_timeouts_total 34798
telemt_upstream_connect_attempt_total 42805
telemt_upstream_connect_success_total 42796
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 42805
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19562
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23167
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3392
telemt_me_reconnect_attempts_total 35979
telemt_me_reconnect_success_total 34698
telemt_me_reader_eof_total 37302
telemt_me_idle_close_by_peer_total 37302
telemt_me_route_drop_no_conn_total 132169
telemt_me_route_drop_channel_closed_total 18
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 318844
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
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 35122
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 34677
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 424
telemt_user_connections_total{user="hello"} 318627
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 12699091556 (11.83 GB)
telemt_user_octets_to_client{user="hello"} 128129522924 (119.33 GB)
telemt_user_unique_ips_current{user="hello"} 38
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 161322.9 (44h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 470989
telemt_connections_bad_total 15551
telemt_handshake_timeouts_total 4408
telemt_upstream_connect_attempt_total 72501
telemt_upstream_connect_success_total 61982
telemt_upstream_connect_fail_total 10519
telemt_upstream_connect_attempts_per_request{bucket="1"} 72501
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36978
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24663
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 332
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10519
telemt_me_keepalive_timeout_total 5282
telemt_me_reconnect_attempts_total 140943
telemt_me_reconnect_success_total 34896
telemt_me_reader_eof_total 39287
telemt_me_idle_close_by_peer_total 39279
telemt_me_route_drop_no_conn_total 168531
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 399706
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1710
telemt_desync_full_logged_total 503
telemt_desync_suppressed_total 1207
telemt_desync_frames_bucket_total{bucket="1_2"} 401
telemt_desync_frames_bucket_total{bucket="3_10"} 647
telemt_desync_frames_bucket_total{bucket="gt_10"} 662
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 38611
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 34886
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3715
telemt_user_connections_total{user="hello"} 418556
telemt_user_connections_current{user="hello"} 116
telemt_user_octets_from_client{user="hello"} 9197807711 (8.57 GB)
telemt_user_octets_to_client{user="hello"} 163327578968 (152.11 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 111494.5 (30h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 183834
telemt_connections_bad_total 26537
telemt_handshake_timeouts_total 1640
telemt_upstream_connect_attempt_total 40172
telemt_upstream_connect_success_total 39801
telemt_upstream_connect_fail_total 371
telemt_upstream_connect_attempts_per_request{bucket="1"} 40172
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20032
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19638
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 131
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 371
telemt_me_keepalive_timeout_total 2378
telemt_me_reconnect_attempts_total 42793
telemt_me_reconnect_success_total 29372
telemt_me_reader_eof_total 31429
telemt_me_idle_close_by_peer_total 31429
telemt_me_route_drop_no_conn_total 54449
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 145716
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 622
telemt_desync_full_logged_total 146
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 83
telemt_me_writer_removed_unexpected_total 30056
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 29354
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 684
telemt_user_connections_total{user="hello"} 150469
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 2243021697 (2.09 GB)
telemt_user_octets_to_client{user="hello"} 68843849375 (64.12 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 161279.1 (44h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 917477
telemt_connections_bad_total 28176
telemt_handshake_timeouts_total 25501
telemt_upstream_connect_attempt_total 33564
telemt_upstream_connect_success_total 33383
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 33564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15645
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17697
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 4580
telemt_me_reconnect_attempts_total 30057
telemt_me_reconnect_success_total 25386
telemt_me_reader_eof_total 27249
telemt_me_idle_close_by_peer_total 27246
telemt_me_route_drop_no_conn_total 436577
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 856670
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 152
telemt_me_writer_removed_unexpected_total 25855
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 25379
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 469
telemt_user_connections_total{user="hello"} 829334
telemt_user_connections_current{user="hello"} 318
telemt_user_octets_from_client{user="hello"} 14472909068 (13.48 GB)
telemt_user_octets_to_client{user="hello"} 419342644212 (390.54 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 45
```