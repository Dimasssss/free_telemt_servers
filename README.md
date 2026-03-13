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

# Server Metrics 2026-03-13 11:13:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 99592.7 (27h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 400055
telemt_connections_bad_total 3195
telemt_handshake_timeouts_total 8145
telemt_upstream_connect_attempt_total 25148
telemt_upstream_connect_success_total 25031
telemt_upstream_connect_fail_total 117
telemt_upstream_connect_attempts_per_request{bucket="1"} 25148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11283
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13700
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 117
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1833
telemt_me_reconnect_attempts_total 23559
telemt_me_reconnect_success_total 20037
telemt_me_reader_eof_total 21407
telemt_me_idle_close_by_peer_total 21406
telemt_me_route_drop_no_conn_total 127305
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 345709
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1123
telemt_desync_full_logged_total 409
telemt_desync_suppressed_total 714
telemt_desync_frames_bucket_total{bucket="1_2"} 233
telemt_desync_frames_bucket_total{bucket="3_10"} 408
telemt_desync_frames_bucket_total{bucket="gt_10"} 482
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 20356
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 20021
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 319
telemt_user_connections_total{user="hello"} 345309
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 6201132928 (5.78 GB)
telemt_user_octets_to_client{user="hello"} 151158932064 (140.78 GB)
telemt_user_unique_ips_current{user="hello"} 114
telemt_user_unique_ips_recent_window{user="hello"} 58
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 99486.2 (27h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182850
telemt_connections_bad_total 1606
telemt_handshake_timeouts_total 1385
telemt_upstream_connect_attempt_total 47945
telemt_upstream_connect_success_total 47268
telemt_upstream_connect_fail_total 677
telemt_upstream_connect_attempts_per_request{bucket="1"} 47945
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19675
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 517
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 677
telemt_me_keepalive_timeout_total 806
telemt_me_reconnect_attempts_total 89990
telemt_me_reconnect_success_total 25795
telemt_me_reader_eof_total 28558
telemt_me_idle_close_by_peer_total 28558
telemt_me_route_drop_no_conn_total 77890
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 156023
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 21
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
telemt_me_writer_removed_unexpected_total 28023
telemt_me_refill_failed_total 2002
telemt_me_writer_restored_same_endpoint_total 25778
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 2228
telemt_user_connections_total{user="hello"} 172302
telemt_user_connections_current{user="hello"} 181
telemt_user_octets_from_client{user="hello"} 1781671348 (1.66 GB)
telemt_user_octets_to_client{user="hello"} 57400822975 (53.46 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 99450.5 (27h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 223326
telemt_connections_bad_total 2052
telemt_handshake_timeouts_total 5252
telemt_upstream_connect_attempt_total 26920
telemt_upstream_connect_success_total 26917
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 26920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12407
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14485
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 815
telemt_me_reconnect_attempts_total 23094
telemt_me_reconnect_success_total 21891
telemt_me_reader_eof_total 23466
telemt_me_idle_close_by_peer_total 23466
telemt_me_route_drop_no_conn_total 83286
telemt_me_route_drop_channel_closed_total 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 207818
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 80
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 42
telemt_desync_frames_bucket_total{bucket="1_2"} 5
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 48
telemt_pool_swap_total 90
telemt_me_writer_removed_unexpected_total 22131
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 21871
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 207737
telemt_user_connections_current{user="hello"} 152
telemt_user_octets_from_client{user="hello"} 9260007660 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 92825694984 (86.45 GB)
telemt_user_unique_ips_current{user="hello"} 75
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 99425.5 (27h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 313098
telemt_connections_bad_total 13724
telemt_handshake_timeouts_total 2282
telemt_upstream_connect_attempt_total 39266
telemt_upstream_connect_success_total 29224
telemt_upstream_connect_fail_total 10042
telemt_upstream_connect_attempts_per_request{bucket="1"} 39266
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14352
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10042
telemt_me_keepalive_timeout_total 3523
telemt_me_reconnect_attempts_total 87440
telemt_me_reconnect_success_total 21395
telemt_me_reader_eof_total 24105
telemt_me_idle_close_by_peer_total 24098
telemt_me_route_drop_no_conn_total 113385
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 269330
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 971
telemt_desync_full_logged_total 289
telemt_desync_suppressed_total 682
telemt_desync_frames_bucket_total{bucket="1_2"} 244
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 370
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 23727
telemt_me_refill_failed_total 2059
telemt_me_writer_restored_same_endpoint_total 21385
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 2332
telemt_user_connections_total{user="hello"} 272051
telemt_user_connections_current{user="hello"} 160
telemt_user_octets_from_client{user="hello"} 5732075874 (5.34 GB)
telemt_user_octets_to_client{user="hello"} 101001285769 (94.06 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 49597.1 (13h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 69275
telemt_connections_bad_total 9879
telemt_handshake_timeouts_total 740
telemt_upstream_connect_attempt_total 19057
telemt_upstream_connect_success_total 18889
telemt_upstream_connect_fail_total 168
telemt_upstream_connect_attempts_per_request{bucket="1"} 19057
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8999
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9832
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 168
telemt_me_keepalive_timeout_total 445
telemt_me_reconnect_attempts_total 20551
telemt_me_reconnect_success_total 14703
telemt_me_reader_eof_total 15689
telemt_me_idle_close_by_peer_total 15689
telemt_me_route_drop_no_conn_total 21408
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 54790
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 87
telemt_desync_full_logged_total 15
telemt_desync_suppressed_total 72
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 37
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 15016
telemt_me_refill_failed_total 181
telemt_me_writer_restored_same_endpoint_total 14685
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 56485
telemt_user_connections_current{user="hello"} 100
telemt_user_octets_from_client{user="hello"} 499490239 (476.35 MB)
telemt_user_octets_to_client{user="hello"} 15464308485 (14.40 GB)
telemt_user_msgs_from_client{user="hello"} 15557
telemt_user_msgs_to_client{user="hello"} 78444
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 99382.2 (27h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 553939
telemt_connections_bad_total 14544
telemt_handshake_timeouts_total 10645
telemt_upstream_connect_attempt_total 21169
telemt_upstream_connect_success_total 21059
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 21169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11164
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 1639
telemt_me_reconnect_attempts_total 20722
telemt_me_reconnect_success_total 16104
telemt_me_reader_eof_total 17292
telemt_me_idle_close_by_peer_total 17289
telemt_me_route_drop_no_conn_total 279252
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 536401
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 172
telemt_desync_suppressed_total 286
telemt_desync_frames_bucket_total{bucket="1_2"} 109
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 174
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 16461
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 16097
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 357
telemt_user_connections_total{user="hello"} 509479
telemt_user_connections_current{user="hello"} 501
telemt_user_octets_from_client{user="hello"} 9252298832 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 278829286252 (259.68 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 70
```