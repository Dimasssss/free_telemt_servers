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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 07:35:20 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 35212.6 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 617621
telemt_connections_bad_total 63679
telemt_connections_current 1460
telemt_connections_me_current 1460
telemt_handshake_timeouts_total 23858
telemt_upstream_connect_attempt_total 6779
telemt_upstream_connect_success_total 6652
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 6779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3233
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3416
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 67
telemt_me_reconnect_attempts_total 6018
telemt_me_reconnect_success_total 4868
telemt_me_reader_eof_total 5167
telemt_me_idle_close_by_peer_total 5166
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 174848
telemt_me_route_drop_channel_closed_total 61
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 465839
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3215
telemt_desync_full_logged_total 897
telemt_desync_suppressed_total 2318
telemt_desync_frames_bucket_total{bucket="1_2"} 1139
telemt_desync_frames_bucket_total{bucket="3_10"} 1203
telemt_desync_frames_bucket_total{bucket="gt_10"} 873
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4958
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4851
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 462955
telemt_user_connections_current{user="hello"} 1460
telemt_user_octets_from_client{user="hello"} 6114400776 (5.69 GB)
telemt_user_octets_to_client{user="hello"} 155636791652 (144.95 GB)
telemt_user_unique_ips_current{user="hello"} 517
telemt_user_unique_ips_recent_window{user="hello"} 232
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 35217.6 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1457023
telemt_connections_bad_total 81368
telemt_connections_current 3949
telemt_connections_me_current 3949
telemt_handshake_timeouts_total 34754
telemt_upstream_connect_attempt_total 6582
telemt_upstream_connect_success_total 6454
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 6581
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3204
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3234
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 26
telemt_me_reconnect_attempts_total 5827
telemt_me_reconnect_success_total 4673
telemt_me_reader_eof_total 4964
telemt_me_idle_close_by_peer_total 4964
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 606648
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1195517
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 34
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5320
telemt_desync_full_logged_total 1785
telemt_desync_suppressed_total 3535
telemt_desync_frames_bucket_total{bucket="1_2"} 946
telemt_desync_frames_bucket_total{bucket="3_10"} 2025
telemt_desync_frames_bucket_total{bucket="gt_10"} 2349
telemt_pool_swap_total 29
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 4797
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4652
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 124
telemt_user_connections_total{user="hello"} 1195438
telemt_user_connections_current{user="hello"} 3949
telemt_user_octets_from_client{user="hello"} 22051126268 (20.54 GB)
telemt_user_octets_to_client{user="hello"} 477703852956 (444.90 GB)
telemt_user_unique_ips_current{user="hello"} 1358
telemt_user_unique_ips_recent_window{user="hello"} 649
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 35214.8 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1238919
telemt_connections_bad_total 177788
telemt_connections_current 3244
telemt_connections_me_current 3244
telemt_handshake_timeouts_total 33497
telemt_upstream_connect_attempt_total 6321
telemt_upstream_connect_success_total 6321
telemt_upstream_connect_attempts_per_request{bucket="1"} 6321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3043
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 4551
telemt_me_reconnect_success_total 4527
telemt_me_reader_eof_total 4795
telemt_me_idle_close_by_peer_total 4795
telemt_me_route_drop_no_conn_total 529909
telemt_me_route_drop_channel_closed_total 40
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 930578
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4344
telemt_desync_full_logged_total 1353
telemt_desync_suppressed_total 2991
telemt_desync_frames_bucket_total{bucket="1_2"} 891
telemt_desync_frames_bucket_total{bucket="3_10"} 1546
telemt_desync_frames_bucket_total{bucket="gt_10"} 1907
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4611
telemt_me_writer_restored_same_endpoint_total 4511
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 930191
telemt_user_connections_current{user="hello"} 3244
telemt_user_octets_from_client{user="hello"} 16885944444 (15.73 GB)
telemt_user_octets_to_client{user="hello"} 470234303732 (437.94 GB)
telemt_user_unique_ips_current{user="hello"} 1060
telemt_user_unique_ips_recent_window{user="hello"} 533
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 35267.9 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1289343
telemt_connections_bad_total 89632
telemt_connections_current 3117
telemt_connections_me_current 3117
telemt_handshake_timeouts_total 31541
telemt_upstream_connect_attempt_total 6145
telemt_upstream_connect_success_total 6145
telemt_upstream_connect_attempts_per_request{bucket="1"} 6145
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3018
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 5398
telemt_me_reconnect_success_total 4337
telemt_me_reader_eof_total 4610
telemt_me_idle_close_by_peer_total 4609
telemt_me_route_drop_no_conn_total 479857
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 885632
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3334
telemt_desync_full_logged_total 1156
telemt_desync_suppressed_total 2178
telemt_desync_frames_bucket_total{bucket="1_2"} 629
telemt_desync_frames_bucket_total{bucket="3_10"} 1307
telemt_desync_frames_bucket_total{bucket="gt_10"} 1398
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 4432
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 4313
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 884447
telemt_user_connections_current{user="hello"} 3117
telemt_user_octets_from_client{user="hello"} 12477845740 (11.62 GB)
telemt_user_octets_to_client{user="hello"} 308035633176 (286.88 GB)
telemt_user_unique_ips_current{user="hello"} 989
telemt_user_unique_ips_recent_window{user="hello"} 479
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 35211.5 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1545641
telemt_connections_bad_total 417311
telemt_connections_current 3297
telemt_connections_me_current 3297
telemt_handshake_timeouts_total 33392
telemt_upstream_connect_attempt_total 6174
telemt_upstream_connect_success_total 6135
telemt_upstream_connect_fail_total 39
telemt_upstream_connect_attempts_per_request{bucket="1"} 6174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3111
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3003
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 39
telemt_me_reconnect_attempts_total 4378
telemt_me_reconnect_success_total 4346
telemt_me_reader_eof_total 4605
telemt_me_idle_close_by_peer_total 4605
telemt_me_route_drop_no_conn_total 388103
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 931249
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4510
telemt_desync_full_logged_total 1408
telemt_desync_suppressed_total 3102
telemt_desync_frames_bucket_total{bucket="1_2"} 1003
telemt_desync_frames_bucket_total{bucket="3_10"} 2036
telemt_desync_frames_bucket_total{bucket="gt_10"} 1471
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 4402
telemt_me_writer_restored_same_endpoint_total 4322
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 56
telemt_user_connections_total{user="hello"} 930936
telemt_user_connections_current{user="hello"} 3297
telemt_user_octets_from_client{user="hello"} 19984332408 (18.61 GB)
telemt_user_octets_to_client{user="hello"} 455627844028 (424.34 GB)
telemt_user_unique_ips_current{user="hello"} 1119
telemt_user_unique_ips_recent_window{user="hello"} 559
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 35223.3 (9h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 259692
telemt_connections_bad_total 13073
telemt_connections_current 875
telemt_connections_me_current 875
telemt_handshake_timeouts_total 2270
telemt_upstream_connect_attempt_total 9207
telemt_upstream_connect_success_total 8965
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 9207
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4405
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4559
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 12549
telemt_me_reconnect_success_total 7174
telemt_me_reader_eof_total 7623
telemt_me_idle_close_by_peer_total 7623
telemt_me_route_drop_no_conn_total 122070
telemt_me_route_drop_channel_closed_total 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 231146
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 355
telemt_desync_full_logged_total 121
telemt_desync_suppressed_total 234
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 96
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 7387
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7144
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 213
telemt_user_connections_total{user="hello"} 231119
telemt_user_connections_current{user="hello"} 875
telemt_user_octets_from_client{user="hello"} 3489200012 (3.25 GB)
telemt_user_octets_to_client{user="hello"} 113052778560 (105.29 GB)
telemt_user_unique_ips_current{user="hello"} 330
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 35213.9 (9h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 980277
telemt_connections_bad_total 91546
telemt_connections_current 3141
telemt_connections_me_current 3141
telemt_handshake_timeouts_total 42758
telemt_upstream_connect_attempt_total 7171
telemt_upstream_connect_success_total 7171
telemt_upstream_connect_attempts_per_request{bucket="1"} 7171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3350
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 6715
telemt_me_reconnect_success_total 5381
telemt_me_reader_eof_total 5713
telemt_me_idle_close_by_peer_total 5713
telemt_me_route_drop_no_conn_total 392779
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 808406
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4787
telemt_desync_full_logged_total 1589
telemt_desync_suppressed_total 3198
telemt_desync_frames_bucket_total{bucket="1_2"} 943
telemt_desync_frames_bucket_total{bucket="3_10"} 1845
telemt_desync_frames_bucket_total{bucket="gt_10"} 1999
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5482
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 5366
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 101
telemt_user_connections_total{user="hello"} 807482
telemt_user_connections_current{user="hello"} 3141
telemt_user_octets_from_client{user="hello"} 11968759052 (11.15 GB)
telemt_user_octets_to_client{user="hello"} 440364820352 (410.12 GB)
telemt_user_unique_ips_current{user="hello"} 986
telemt_user_unique_ips_recent_window{user="hello"} 448
```