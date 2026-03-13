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

# Server Metrics 2026-03-13 05:25:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 78724.1 (21h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 299203
telemt_connections_bad_total 3066
telemt_handshake_timeouts_total 6155
telemt_upstream_connect_attempt_total 19847
telemt_upstream_connect_success_total 19754
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 19847
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8841
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10865
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1560
telemt_me_reconnect_attempts_total 19291
telemt_me_reconnect_success_total 15794
telemt_me_reader_eof_total 16890
telemt_me_idle_close_by_peer_total 16889
telemt_me_route_drop_no_conn_total 93286
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 251839
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 860
telemt_desync_full_logged_total 320
telemt_desync_suppressed_total 540
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 313
telemt_desync_frames_bucket_total{bucket="gt_10"} 376
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 16072
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15778
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 251776
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 4306488516 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 123213839212 (114.75 GB)
telemt_user_unique_ips_current{user="hello"} 83
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 78617.0 (21h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136800
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 1034
telemt_upstream_connect_attempt_total 41786
telemt_upstream_connect_success_total 41256
telemt_upstream_connect_fail_total 530
telemt_upstream_connect_attempts_per_request{bucket="1"} 41786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24609
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16139
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 530
telemt_me_keepalive_timeout_total 585
telemt_me_reconnect_attempts_total 67378
telemt_me_reconnect_success_total 20814
telemt_me_reader_eof_total 22918
telemt_me_idle_close_by_peer_total 22918
telemt_me_route_drop_no_conn_total 50787
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113489
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 22433
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 20799
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1619
telemt_user_connections_total{user="hello"} 129989
telemt_user_connections_current{user="hello"} 104
telemt_user_octets_from_client{user="hello"} 1353473444 (1.26 GB)
telemt_user_octets_to_client{user="hello"} 39454948739 (36.75 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 78580.5 (21h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 165454
telemt_connections_bad_total 1859
telemt_handshake_timeouts_total 2677
telemt_upstream_connect_attempt_total 21697
telemt_upstream_connect_success_total 21695
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21697
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 461
telemt_me_reconnect_attempts_total 18881
telemt_me_reconnect_success_total 17715
telemt_me_reader_eof_total 18983
telemt_me_idle_close_by_peer_total 18983
telemt_me_route_drop_no_conn_total 64186
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 154748
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 71
telemt_me_writer_removed_unexpected_total 17907
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17695
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 192
telemt_user_connections_total{user="hello"} 154675
telemt_user_connections_current{user="hello"} 103
telemt_user_octets_from_client{user="hello"} 2909511700 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 71017321060 (66.14 GB)
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 78556.2 (21h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238860
telemt_connections_bad_total 13565
telemt_handshake_timeouts_total 1796
telemt_upstream_connect_attempt_total 33927
telemt_upstream_connect_success_total 24028
telemt_upstream_connect_fail_total 9899
telemt_upstream_connect_attempts_per_request{bucket="1"} 33927
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11749
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9899
telemt_me_keepalive_timeout_total 3316
telemt_me_reconnect_attempts_total 68759
telemt_me_reconnect_success_total 17229
telemt_me_reader_eof_total 19362
telemt_me_idle_close_by_peer_total 19355
telemt_me_route_drop_no_conn_total 87051
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 200127
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 564
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 405
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 212
telemt_desync_frames_bucket_total{bucket="gt_10"} 212
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 19063
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 17219
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1834
telemt_user_connections_total{user="hello"} 202870
telemt_user_connections_current{user="hello"} 127
telemt_user_octets_from_client{user="hello"} 3286908982 (3.06 GB)
telemt_user_octets_to_client{user="hello"} 80940441397 (75.38 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 45
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 28727.8 (7h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 30311
telemt_connections_bad_total 5399
telemt_handshake_timeouts_total 130
telemt_upstream_connect_attempt_total 9552
telemt_upstream_connect_success_total 9461
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 9552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4117
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5310
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 34
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 231
telemt_me_reconnect_attempts_total 8987
telemt_me_reconnect_success_total 8029
telemt_me_reader_eof_total 8554
telemt_me_idle_close_by_peer_total 8554
telemt_me_route_drop_no_conn_total 8446
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23956
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 8135
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 8011
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 23956
telemt_user_connections_current{user="hello"} 48
telemt_user_octets_from_client{user="hello"} 197057728 (187.93 MB)
telemt_user_octets_to_client{user="hello"} 9389109240 (8.74 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 78512.8 (21h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 402442
telemt_connections_bad_total 7744
telemt_handshake_timeouts_total 2979
telemt_upstream_connect_attempt_total 16736
telemt_upstream_connect_success_total 16642
telemt_upstream_connect_fail_total 94
telemt_upstream_connect_attempts_per_request{bucket="1"} 16736
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7763
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8854
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1448
telemt_me_reconnect_attempts_total 16352
telemt_me_reconnect_success_total 12721
telemt_me_reader_eof_total 13664
telemt_me_idle_close_by_peer_total 13661
telemt_me_route_drop_no_conn_total 179086
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 391495
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 331
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 73
telemt_me_writer_removed_unexpected_total 12996
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12714
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 379744
telemt_user_connections_current{user="hello"} 317
telemt_user_octets_from_client{user="hello"} 6273710304 (5.84 GB)
telemt_user_octets_to_client{user="hello"} 222522662548 (207.24 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 49
```