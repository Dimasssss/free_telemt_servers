# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 23:26:28 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 22133.9 (6h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 463033
telemt_connections_bad_total 29314
telemt_connections_current 770
telemt_connections_me_current 770
telemt_handshake_timeouts_total 7065
telemt_upstream_connect_attempt_total 3691
telemt_upstream_connect_success_total 3660
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 3691
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1858
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2559
telemt_me_reconnect_success_total 2540
telemt_me_reader_eof_total 2695
telemt_me_idle_close_by_peer_total 2695
telemt_me_route_drop_no_conn_total 137513
telemt_me_route_drop_channel_closed_total 52
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 367465
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1950
telemt_desync_full_logged_total 683
telemt_desync_suppressed_total 1267
telemt_desync_frames_bucket_total{bucket="1_2"} 406
telemt_desync_frames_bucket_total{bucket="3_10"} 637
telemt_desync_frames_bucket_total{bucket="gt_10"} 907
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 2592
telemt_me_writer_restored_same_endpoint_total 2527
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 52
telemt_user_connections_total{user="hello"} 367737
telemt_user_connections_current{user="hello"} 770
telemt_user_octets_from_client{user="hello"} 23164486720 (21.57 GB)
telemt_user_octets_to_client{user="hello"} 135487923844 (126.18 GB)
telemt_user_unique_ips_current{user="hello"} 291
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 38589.4 (10h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2865789
telemt_connections_bad_total 122908
telemt_connections_current 1413
telemt_connections_me_current 1413
telemt_handshake_timeouts_total 58814
telemt_upstream_connect_attempt_total 7722
telemt_upstream_connect_success_total 7599
telemt_upstream_connect_fail_total 123
telemt_upstream_connect_attempts_per_request{bucket="1"} 7722
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4561
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 123
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8682
telemt_me_reconnect_success_total 4447
telemt_me_reader_eof_total 4768
telemt_me_idle_close_by_peer_total 4768
telemt_me_route_drop_no_conn_total 1465932
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2449815
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10720
telemt_desync_full_logged_total 3534
telemt_desync_suppressed_total 7186
telemt_desync_frames_bucket_total{bucket="1_2"} 2007
telemt_desync_frames_bucket_total{bucket="3_10"} 4203
telemt_desync_frames_bucket_total{bucket="gt_10"} 4510
telemt_pool_swap_total 31
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 4627
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4392
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 2449644
telemt_user_connections_current{user="hello"} 1413
telemt_user_octets_from_client{user="hello"} 38249008818 (35.62 GB)
telemt_user_octets_to_client{user="hello"} 884743003590 (823.98 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 650
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 38567.3 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2787960
telemt_connections_bad_total 464655
telemt_connections_current 1085
telemt_connections_me_current 1085
telemt_handshake_timeouts_total 37061
telemt_upstream_connect_attempt_total 6084
telemt_upstream_connect_success_total 6036
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 6084
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3088
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2932
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 5041
telemt_me_reconnect_success_total 4111
telemt_me_reader_eof_total 4289
telemt_me_idle_close_by_peer_total 4288
telemt_me_route_drop_no_conn_total 1884387
telemt_me_route_drop_channel_closed_total 169
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1940670
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7510
telemt_desync_full_logged_total 2267
telemt_desync_suppressed_total 5243
telemt_desync_frames_bucket_total{bucket="1_2"} 1848
telemt_desync_frames_bucket_total{bucket="3_10"} 2859
telemt_desync_frames_bucket_total{bucket="gt_10"} 2803
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 4146
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 4110
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 1936461
telemt_user_connections_current{user="hello"} 1085
telemt_user_octets_from_client{user="hello"} 29061296572 (27.07 GB)
telemt_user_octets_to_client{user="hello"} 735601100832 (685.08 GB)
telemt_user_unique_ips_current{user="hello"} 470
telemt_user_unique_ips_recent_window{user="hello"} 96
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 38555.3 (10h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2430989
telemt_connections_bad_total 100203
telemt_connections_current 1042
telemt_connections_me_current 1042
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 29864
telemt_upstream_connect_attempt_total 53031
telemt_upstream_connect_success_total 48877
telemt_upstream_connect_fail_total 4154
telemt_upstream_connect_attempts_per_request{bucket="1"} 53031
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 41590
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6746
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 516
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4154
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7385
telemt_me_reconnect_success_total 4633
telemt_me_reader_eof_total 4797
telemt_me_idle_close_by_peer_total 4796
telemt_me_route_drop_no_conn_total 1839510
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2050035
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8144
telemt_desync_full_logged_total 2569
telemt_desync_suppressed_total 5575
telemt_desync_frames_bucket_total{bucket="1_2"} 1995
telemt_desync_frames_bucket_total{bucket="3_10"} 2961
telemt_desync_frames_bucket_total{bucket="gt_10"} 3188
telemt_pool_swap_total 24
telemt_me_writer_close_signal_drop_total 403
telemt_me_writer_removed_unexpected_total 5198
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4629
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 565
telemt_user_connections_total{user="hello"} 2091191
telemt_user_connections_current{user="hello"} 1042
telemt_user_octets_from_client{user="hello"} 34125911571 (31.78 GB)
telemt_user_octets_to_client{user="hello"} 563445634451 (524.75 GB)
telemt_user_msgs_from_client{user="hello"} 239211
telemt_user_msgs_to_client{user="hello"} 1739348
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 92278.7 (25h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6142327
telemt_connections_bad_total 1037328
telemt_connections_current 1212
telemt_connections_me_current 1212
telemt_relay_adaptive_promotions_total 27
telemt_relay_adaptive_demotions_total 3535
telemt_relay_adaptive_hard_promotions_total 25
telemt_handshake_timeouts_total 110487
telemt_upstream_connect_attempt_total 116767
telemt_upstream_connect_success_total 85442
telemt_upstream_connect_fail_total 31325
telemt_upstream_connect_attempts_per_request{bucket="1"} 116767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 72981
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31325
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77355
telemt_me_reconnect_success_total 11818
telemt_me_reader_eof_total 12602
telemt_me_idle_close_by_peer_total 12591
telemt_me_route_drop_no_conn_total 2765468
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4338843
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 19098
telemt_desync_full_logged_total 5982
telemt_desync_suppressed_total 13116
telemt_desync_frames_bucket_total{bucket="1_2"} 3338
telemt_desync_frames_bucket_total{bucket="3_10"} 7839
telemt_desync_frames_bucket_total{bucket="gt_10"} 7921
telemt_pool_swap_total 78
telemt_me_writer_removed_unexpected_total 12105
telemt_me_refill_failed_total 2043
telemt_me_writer_restored_same_endpoint_total 11793
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 4406752
telemt_user_connections_current{user="hello"} 1212
telemt_user_octets_from_client{user="hello"} 67910604098 (63.25 GB)
telemt_user_octets_to_client{user="hello"} 1707735935660 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 702760
telemt_user_msgs_to_client{user="hello"} 2862853
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 114
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 38518.5 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 671271
telemt_connections_bad_total 67443
telemt_connections_current 298
telemt_connections_me_current 298
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12817
telemt_upstream_connect_attempt_total 11892
telemt_upstream_connect_success_total 11562
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 11892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4757
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5967
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 658
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5288
telemt_me_reconnect_success_total 5185
telemt_me_reader_eof_total 5405
telemt_me_idle_close_by_peer_total 5402
telemt_me_route_drop_no_conn_total 454716
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 554070
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1380
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 150
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5231
telemt_me_writer_restored_same_endpoint_total 5176
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 542214
telemt_user_connections_current{user="hello"} 298
telemt_user_octets_from_client{user="hello"} 7059369167 (6.57 GB)
telemt_user_octets_to_client{user="hello"} 130446617058 (121.49 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 124
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 38519.8 (10h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1935817
telemt_connections_bad_total 117135
telemt_connections_current 1223
telemt_connections_me_current 1223
telemt_handshake_timeouts_total 35794
telemt_upstream_connect_attempt_total 6639
telemt_upstream_connect_success_total 6588
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 6639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3526
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3026
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4692
telemt_me_reconnect_success_total 4655
telemt_me_reader_eof_total 4907
telemt_me_idle_close_by_peer_total 4907
telemt_me_route_drop_no_conn_total 717512
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1666552
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8870
telemt_desync_full_logged_total 2827
telemt_desync_suppressed_total 6043
telemt_desync_frames_bucket_total{bucket="1_2"} 1621
telemt_desync_frames_bucket_total{bucket="3_10"} 3115
telemt_desync_frames_bucket_total{bucket="gt_10"} 4134
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4732
telemt_me_writer_restored_same_endpoint_total 4638
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1665689
telemt_user_connections_current{user="hello"} 1223
telemt_user_octets_from_client{user="hello"} 28236838888 (26.30 GB)
telemt_user_octets_to_client{user="hello"} 842151949012 (784.32 GB)
telemt_user_unique_ips_current{user="hello"} 498
telemt_user_unique_ips_recent_window{user="hello"} 98
```