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

# Server Metrics 2026-03-15 11:34:13 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 47985.2 (13h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205902
telemt_connections_bad_total 1390
telemt_handshake_timeouts_total 4470
telemt_upstream_connect_attempt_total 12233
telemt_upstream_connect_success_total 12168
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 12233
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6756
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13120
telemt_me_reconnect_success_total 9751
telemt_me_reader_eof_total 10424
telemt_me_idle_close_by_peer_total 10424
telemt_me_route_drop_no_conn_total 419449
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252863
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1476
telemt_desync_full_logged_total 587
telemt_desync_suppressed_total 889
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 585
telemt_desync_frames_bucket_total{bucket="gt_10"} 648
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 9952
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 9720
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 201
telemt_user_connections_total{user="hello"} 192121
telemt_user_connections_current{user="hello"} 445
telemt_user_octets_from_client{user="hello"} 3626100036 (3.38 GB)
telemt_user_octets_to_client{user="hello"} 188265399416 (175.34 GB)
telemt_user_unique_ips_current{user="hello"} 131
telemt_user_unique_ips_recent_window{user="hello"} 56
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 47991.4 (13h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 68714
telemt_connections_bad_total 2335
telemt_handshake_timeouts_total 3581
telemt_upstream_connect_attempt_total 13018
telemt_upstream_connect_success_total 13018
telemt_upstream_connect_attempts_per_request{bucket="1"} 13018
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5596
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7328
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 94
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 12907
telemt_me_reconnect_success_total 10576
telemt_me_reader_eof_total 11333
telemt_me_idle_close_by_peer_total 11333
telemt_me_route_drop_no_conn_total 32248
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 60544
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10763
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 10560
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 60543
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 1098242424 (1.02 GB)
telemt_user_octets_to_client{user="hello"} 25065104632 (23.34 GB)
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 47984.1 (13h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75841
telemt_connections_bad_total 1011
telemt_handshake_timeouts_total 2553
telemt_upstream_connect_attempt_total 13695
telemt_upstream_connect_success_total 13687
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 13695
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5913
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7751
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 13386
telemt_me_reconnect_success_total 11250
telemt_me_reader_eof_total 12059
telemt_me_idle_close_by_peer_total 12059
telemt_me_route_drop_no_conn_total 29029
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69000
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 11422
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 11242
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 68917
telemt_user_connections_current{user="hello"} 136
telemt_user_octets_from_client{user="hello"} 9476522728 (8.83 GB)
telemt_user_octets_to_client{user="hello"} 42852182088 (39.91 GB)
telemt_user_unique_ips_current{user="hello"} 60
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 47983.6 (13h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101358
telemt_connections_bad_total 295
telemt_handshake_timeouts_total 673
telemt_upstream_connect_attempt_total 11367
telemt_upstream_connect_success_total 11366
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11367
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5437
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5894
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9003
telemt_me_reconnect_success_total 8958
telemt_me_reader_eof_total 9562
telemt_me_idle_close_by_peer_total 9562
telemt_me_route_drop_no_conn_total 40721
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 92543
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 220
telemt_desync_full_logged_total 66
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 51
telemt_desync_frames_bucket_total{bucket="3_10"} 91
telemt_desync_frames_bucket_total{bucket="gt_10"} 78
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 9055
telemt_me_writer_restored_same_endpoint_total 8947
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 97
telemt_user_connections_total{user="hello"} 92465
telemt_user_connections_current{user="hello"} 228
telemt_user_octets_from_client{user="hello"} 1703094960 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 53336515200 (49.67 GB)
telemt_user_unique_ips_current{user="hello"} 71
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 23055.2 (6h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47869
telemt_connections_bad_total 9894
telemt_handshake_timeouts_total 844
telemt_upstream_connect_attempt_total 7704
telemt_upstream_connect_success_total 7647
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 7704
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3452
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4167
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_reconnect_attempts_total 100724
telemt_me_reconnect_success_total 6310
telemt_me_reader_eof_total 6555
telemt_me_idle_close_by_peer_total 6555
telemt_me_route_drop_no_conn_total 18257
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 35968
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 70
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 57
telemt_desync_frames_bucket_total{bucket="1_2"} 10
telemt_desync_frames_bucket_total{bucket="3_10"} 29
telemt_desync_frames_bucket_total{bucket="gt_10"} 31
telemt_pool_swap_total 14
telemt_me_writer_removed_unexpected_total 6295
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6206
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 36106
telemt_user_connections_current{user="hello"} 106
telemt_user_octets_from_client{user="hello"} 549958517 (524.48 MB)
telemt_user_octets_to_client{user="hello"} 14305563775 (13.32 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 47983.0 (13h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 268314
telemt_connections_bad_total 46639
telemt_handshake_timeouts_total 2009
telemt_upstream_connect_attempt_total 10218
telemt_upstream_connect_success_total 10156
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 10218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5115
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5038
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 7784
telemt_me_reconnect_success_total 7734
telemt_me_reader_eof_total 8241
telemt_me_idle_close_by_peer_total 8241
telemt_me_route_drop_no_conn_total 118764
telemt_me_route_drop_channel_closed_total 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211844
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 88
telemt_desync_full_logged_total 48
telemt_desync_suppressed_total 40
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 42
telemt_desync_frames_bucket_total{bucket="gt_10"} 33
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7796
telemt_me_writer_restored_same_endpoint_total 7707
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 210210
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 4756508004 (4.43 GB)
telemt_user_octets_to_client{user="hello"} 100601416060 (93.69 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 65
```