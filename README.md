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

# Server Metrics 2026-03-16 08:50:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 124558.4 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 587637
telemt_connections_bad_total 7811
telemt_handshake_timeouts_total 20718
telemt_upstream_connect_attempt_total 29026
telemt_upstream_connect_success_total 28886
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 29026
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15979
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 26154
telemt_me_reconnect_success_total 22715
telemt_me_reader_eof_total 24295
telemt_me_idle_close_by_peer_total 24295
telemt_me_route_drop_no_conn_total 531546
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 580111
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2764
telemt_desync_full_logged_total 1082
telemt_desync_suppressed_total 1682
telemt_desync_frames_bucket_total{bucket="1_2"} 606
telemt_desync_frames_bucket_total{bucket="3_10"} 1062
telemt_desync_frames_bucket_total{bucket="gt_10"} 1096
telemt_pool_swap_total 121
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 23074
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 22681
telemt_me_writer_restored_fallback_total 34
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 359
telemt_user_connections_total{user="hello"} 518922
telemt_user_connections_current{user="hello"} 512
telemt_user_octets_from_client{user="hello"} 10118724652 (9.42 GB)
telemt_user_octets_to_client{user="hello"} 328094339644 (305.56 GB)
telemt_user_unique_ips_current{user="hello"} 165
telemt_user_unique_ips_recent_window{user="hello"} 77
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 124565.6 (34h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 238777
telemt_connections_bad_total 3285
telemt_handshake_timeouts_total 15214
telemt_upstream_connect_attempt_total 33427
telemt_upstream_connect_success_total 33352
telemt_upstream_connect_fail_total 75
telemt_upstream_connect_attempts_per_request{bucket="1"} 33427
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14371
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18323
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 658
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 75
telemt_me_keepalive_timeout_total 1307
telemt_me_reconnect_attempts_total 36046
telemt_me_reconnect_success_total 26757
telemt_me_reader_eof_total 28705
telemt_me_idle_close_by_peer_total 28704
telemt_me_route_drop_no_conn_total 115537
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 211998
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 174
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 122
telemt_desync_frames_bucket_total{bucket="1_2"} 33
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 75
telemt_pool_swap_total 108
telemt_me_writer_removed_unexpected_total 27415
telemt_me_refill_failed_total 282
telemt_me_writer_restored_same_endpoint_total 26741
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 658
telemt_user_connections_total{user="hello"} 211536
telemt_user_connections_current{user="hello"} 320
telemt_user_octets_from_client{user="hello"} 4764600381 (4.44 GB)
telemt_user_octets_to_client{user="hello"} 118293437388 (110.17 GB)
telemt_user_msgs_from_client{user="hello"} 721
telemt_user_msgs_to_client{user="hello"} 1482
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 124558.6 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251226
telemt_connections_bad_total 5745
telemt_handshake_timeouts_total 4800
telemt_upstream_connect_attempt_total 34678
telemt_upstream_connect_success_total 34670
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 34678
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 54
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 35834
telemt_me_reconnect_success_total 28422
telemt_me_reader_eof_total 30585
telemt_me_idle_close_by_peer_total 30584
telemt_me_route_drop_no_conn_total 87655
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 202550
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 100
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 61
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 45
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 114
telemt_me_writer_removed_unexpected_total 28934
telemt_me_refill_failed_total 227
telemt_me_writer_restored_same_endpoint_total 28414
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 512
telemt_user_connections_total{user="hello"} 202252
telemt_user_connections_current{user="hello"} 208
telemt_user_octets_from_client{user="hello"} 17562955637 (16.36 GB)
telemt_user_octets_to_client{user="hello"} 114752186324 (106.87 GB)
telemt_user_msgs_from_client{user="hello"} 7
telemt_user_msgs_to_client{user="hello"} 46
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 124557.7 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354021
telemt_connections_bad_total 1370
telemt_handshake_timeouts_total 3043
telemt_upstream_connect_attempt_total 28806
telemt_upstream_connect_success_total 28772
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 28806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13797
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14817
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 143
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 22722
telemt_me_reconnect_success_total 22578
telemt_me_reader_eof_total 24108
telemt_me_idle_close_by_peer_total 24107
telemt_me_route_drop_no_conn_total 123596
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 326893
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1194
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 784
telemt_desync_frames_bucket_total{bucket="1_2"} 245
telemt_desync_frames_bucket_total{bucket="3_10"} 513
telemt_desync_frames_bucket_total{bucket="gt_10"} 436
telemt_pool_swap_total 120
telemt_me_writer_removed_unexpected_total 22873
telemt_me_writer_restored_same_endpoint_total 22567
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 295
telemt_user_connections_total{user="hello"} 326779
telemt_user_connections_current{user="hello"} 343
telemt_user_octets_from_client{user="hello"} 5167895218 (4.81 GB)
telemt_user_octets_to_client{user="hello"} 136334192756 (126.97 GB)
telemt_user_msgs_from_client{user="hello"} 25
telemt_user_msgs_to_client{user="hello"} 50
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 99629.0 (27h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 228755
telemt_connections_bad_total 36731
telemt_handshake_timeouts_total 3981
telemt_upstream_connect_attempt_total 28377
telemt_upstream_connect_success_total 28221
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 28377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15581
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 148
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 117608
telemt_me_reconnect_success_total 23111
telemt_me_reader_eof_total 24556
telemt_me_idle_close_by_peer_total 24556
telemt_me_route_drop_no_conn_total 71444
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181507
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 562
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 427
telemt_desync_frames_bucket_total{bucket="1_2"} 86
telemt_desync_frames_bucket_total{bucket="3_10"} 233
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 86
telemt_me_writer_removed_unexpected_total 23302
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 23007
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 181125
telemt_user_connections_current{user="hello"} 149
telemt_user_octets_from_client{user="hello"} 2415302205 (2.25 GB)
telemt_user_octets_to_client{user="hello"} 74753058159 (69.62 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 124557.0 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 832762
telemt_connections_bad_total 72514
telemt_handshake_timeouts_total 9666
telemt_upstream_connect_attempt_total 26075
telemt_upstream_connect_success_total 25938
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 26075
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13498
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 21085
telemt_me_reconnect_success_total 19735
telemt_me_reader_eof_total 21080
telemt_me_idle_close_by_peer_total 21080
telemt_me_route_drop_no_conn_total 653631
telemt_me_route_drop_channel_closed_total 114
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 825502
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 336
telemt_desync_full_logged_total 96
telemt_desync_suppressed_total 240
telemt_desync_frames_bucket_total{bucket="1_2"} 171
telemt_desync_frames_bucket_total{bucket="3_10"} 98
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 119
telemt_me_writer_removed_unexpected_total 20012
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 19708
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 277
telemt_user_connections_total{user="hello"} 684132
telemt_user_connections_current{user="hello"} 681
telemt_user_octets_from_client{user="hello"} 14811044464 (13.79 GB)
telemt_user_octets_to_client{user="hello"} 412830388032 (384.48 GB)
telemt_user_unique_ips_current{user="hello"} 222
telemt_user_unique_ips_recent_window{user="hello"} 102
```