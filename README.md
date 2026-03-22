# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 15:18:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 65514.6 (18h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2278944
telemt_connections_bad_total 123218
telemt_connections_current 1831
telemt_connections_me_current 1831
telemt_handshake_timeouts_total 85513
telemt_upstream_connect_attempt_total 24261
telemt_upstream_connect_success_total 24260
telemt_upstream_connect_attempts_per_request{bucket="1"} 24260
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8448
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15745
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 54
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 150
telemt_me_reconnect_attempts_total 1001
telemt_me_reconnect_success_total 409
telemt_me_reader_eof_total 412
telemt_me_idle_close_by_peer_total 412
telemt_me_route_drop_no_conn_total 1846847
telemt_me_route_drop_channel_closed_total 745
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1933549
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 514
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 9591
telemt_desync_full_logged_total 2962
telemt_desync_suppressed_total 6629
telemt_desync_frames_bucket_total{bucket="1_2"} 2618
telemt_desync_frames_bucket_total{bucket="3_10"} 3597
telemt_desync_frames_bucket_total{bucket="gt_10"} 3376
telemt_pool_swap_total 72
telemt_pool_force_close_total 2217
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 404
telemt_me_draining_writers_reap_progress_total 22172
telemt_me_writer_removed_unexpected_total 399
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1598
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 20774
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2170
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 47
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19955
telemt_me_writer_teardown_success_total{mode="normal"} 22372
telemt_me_writer_teardown_noop_total 22177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 38110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 39555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 43596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 44352
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 44546
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 44549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 44549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 44549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 44549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 44549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 44549
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 194.034689
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 44549
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 404
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 360
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 1930407
telemt_user_connections_current{user="hello"} 1831
telemt_user_octets_from_client{user="hello"} 29194773684 (27.19 GB)
telemt_user_octets_to_client{user="hello"} 520257587468 (484.53 GB)
telemt_user_unique_ips_current{user="hello"} 654
telemt_user_unique_ips_recent_window{user="hello"} 256
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 78880.5 (21h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3508400
telemt_connections_bad_total 314464
telemt_connections_current 804
telemt_connections_me_current 804
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 83678
telemt_upstream_connect_attempt_total 49946
telemt_upstream_connect_success_total 49344
telemt_upstream_connect_fail_total 530
telemt_upstream_connect_attempts_per_request{bucket="1"} 49874
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29069
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20114
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 161
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 530
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 5680
telemt_me_reconnect_success_total 1951
telemt_me_reader_eof_total 1878
telemt_me_idle_close_by_peer_total 1878
telemt_me_route_drop_no_conn_total 3505427
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2784394
telemt_me_endpoint_quarantine_total 642
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 36
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 36
telemt_me_single_endpoint_shadow_rotate_total 612
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 10733
telemt_desync_full_logged_total 5952
telemt_desync_suppressed_total 4781
telemt_desync_frames_bucket_total{bucket="1_2"} 2520
telemt_desync_frames_bucket_total{bucket="3_10"} 4233
telemt_desync_frames_bucket_total{bucket="gt_10"} 3980
telemt_pool_swap_total 75
telemt_pool_force_close_total 2228
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 186
telemt_me_draining_writers_reap_progress_total 31272
telemt_me_writer_removed_unexpected_total 1834
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3624
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29485
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 318
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29044
telemt_me_writer_teardown_success_total{mode="normal"} 33109
telemt_me_writer_teardown_noop_total 31272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62806
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 64381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 64381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 64381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 64381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 64381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 64381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 64381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 64381
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.569388
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 64381
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 186
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1661
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 2795753
telemt_user_connections_current{user="hello"} 804
telemt_user_octets_from_client{user="hello"} 34051961355 (31.71 GB)
telemt_user_octets_to_client{user="hello"} 606514675906 (564.86 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 511
telemt_user_unique_ips_recent_window{user="hello"} 241
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 153740.4 (42h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 15104455
telemt_connections_bad_total 1384738
telemt_connections_current 2196
telemt_connections_me_current 2196
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 366665
telemt_upstream_connect_attempt_total 69811
telemt_upstream_connect_success_total 69716
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 69733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 35238
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32812
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1659
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2566
telemt_me_reconnect_success_total 1331
telemt_me_reader_eof_total 1267
telemt_me_idle_close_by_peer_total 1266
telemt_me_route_drop_no_conn_total 13727817
telemt_me_route_drop_channel_closed_total 134
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12088070
telemt_me_endpoint_quarantine_total 971
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 1144
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 48743
telemt_desync_full_logged_total 15304
telemt_desync_suppressed_total 33439
telemt_desync_frames_bucket_total{bucket="1_2"} 10980
telemt_desync_frames_bucket_total{bucket="3_10"} 19076
telemt_desync_frames_bucket_total{bucket="gt_10"} 18687
telemt_pool_swap_total 165
telemt_pool_force_close_total 5630
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 920
telemt_me_draining_writers_reap_progress_total 50546
telemt_me_writer_removed_unexpected_total 1223
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4403
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46671
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 42
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5174
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 456
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44916
telemt_me_writer_teardown_success_total{mode="normal"} 51074
telemt_me_writer_teardown_noop_total 50596
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 91796
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94998
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 98668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101661
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101668
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101670
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 290.443226
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101670
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 920
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 1142
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 12089563
telemt_user_connections_current{user="hello"} 2196
telemt_user_octets_from_client{user="hello"} 169191856173 (157.57 GB)
telemt_user_octets_to_client{user="hello"} 3102059624443 (2.82 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 910
telemt_user_unique_ips_recent_window{user="hello"} 298
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 153741.9 (42h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10889527
telemt_connections_bad_total 1049296
telemt_connections_current 1709
telemt_connections_me_current 1709
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 322144
telemt_upstream_connect_attempt_total 81997
telemt_upstream_connect_success_total 80847
telemt_upstream_connect_fail_total 826
telemt_upstream_connect_attempts_per_request{bucket="1"} 81673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32714
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3692
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 826
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3857
telemt_me_reconnect_success_total 1552
telemt_me_reader_eof_total 1427
telemt_me_idle_close_by_peer_total 1427
telemt_me_route_drop_no_conn_total 4319881
telemt_me_route_drop_channel_closed_total 476
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8129226
telemt_me_endpoint_quarantine_total 962
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 1163
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_desync_total 36068
telemt_desync_full_logged_total 12113
telemt_desync_suppressed_total 23955
telemt_desync_frames_bucket_total{bucket="1_2"} 8855
telemt_desync_frames_bucket_total{bucket="3_10"} 13878
telemt_desync_frames_bucket_total{bucket="gt_10"} 13335
telemt_pool_swap_total 163
telemt_pool_force_close_total 5067
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 649
telemt_me_draining_writers_reap_progress_total 48860
telemt_me_writer_removed_unexpected_total 1459
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4499
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45677
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 16
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4597
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43793
telemt_me_writer_teardown_success_total{mode="normal"} 50176
telemt_me_writer_teardown_noop_total 48876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92895
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 95774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 96834
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 97922
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 98636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 98967
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 99042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 99044
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 99050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 99052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 99052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 99052
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 99052
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 98.849266
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 99052
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 649
telemt_me_refill_failed_total 125
telemt_me_writer_restored_same_endpoint_total 1323
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 8068107
telemt_user_connections_current{user="hello"} 1709
telemt_user_octets_from_client{user="hello"} 202842224713 (188.91 GB)
telemt_user_octets_to_client{user="hello"} 3636675060186 (3.31 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 700
telemt_user_unique_ips_recent_window{user="hello"} 212
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 153706.7 (42h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10327684
telemt_connections_bad_total 883852
telemt_connections_current 1400
telemt_connections_me_current 1400
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 329566
telemt_upstream_connect_attempt_total 67250
telemt_upstream_connect_success_total 66324
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 66506
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31782
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31256
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2051
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4618
telemt_me_reconnect_success_total 1858
telemt_me_reader_eof_total 1616
telemt_me_idle_close_by_peer_total 1615
telemt_me_route_drop_no_conn_total 5094060
telemt_me_route_drop_channel_closed_total 352
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7797613
telemt_me_endpoint_quarantine_total 1057
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 31
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 31
telemt_me_single_endpoint_shadow_rotate_total 1128
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 55
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 35744
telemt_desync_full_logged_total 11847
telemt_desync_suppressed_total 23897
telemt_desync_frames_bucket_total{bucket="1_2"} 9046
telemt_desync_frames_bucket_total{bucket="3_10"} 13653
telemt_desync_frames_bucket_total{bucket="gt_10"} 13045
telemt_pool_swap_total 160
telemt_pool_force_close_total 5021
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 681
telemt_me_draining_writers_reap_progress_total 49325
telemt_me_writer_removed_unexpected_total 1756
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4951
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46042
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4484
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 537
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 44304
telemt_me_writer_teardown_success_total{mode="normal"} 50993
telemt_me_writer_teardown_noop_total 49396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 95003
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 97458
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 98350
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 99346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 99915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100302
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100338
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100389
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3169.903800
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100389
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 681
telemt_me_refill_failed_total 146
telemt_me_writer_restored_same_endpoint_total 1612
telemt_me_writer_restored_fallback_total 8
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 136
telemt_user_connections_total{user="hello"} 7790742
telemt_user_connections_current{user="hello"} 1400
telemt_user_octets_from_client{user="hello"} 180086390373 (167.72 GB)
telemt_user_octets_to_client{user="hello"} 3235252458189 (2.94 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 553
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 23985.8 (6h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9919637
telemt_connections_bad_total 607652
telemt_connections_current 2176
telemt_connections_me_current 2176
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 162988
telemt_upstream_connect_attempt_total 34189
telemt_upstream_connect_success_total 32473
telemt_upstream_connect_fail_total 1237
telemt_upstream_connect_attempts_per_request{bucket="1"} 33710
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17784
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8418
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 988
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1237
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 5645
telemt_me_reconnect_success_total 653
telemt_me_reader_eof_total 401
telemt_me_idle_close_by_peer_total 401
telemt_me_route_drop_no_conn_total 24809985
telemt_me_route_drop_channel_closed_total 39
telemt_me_route_drop_queue_full_total 26
telemt_me_route_drop_queue_full_profile_total{profile="high"} 26
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8271544
telemt_me_endpoint_quarantine_total 149
telemt_me_single_endpoint_outage_enter_total 45
telemt_me_single_endpoint_outage_exit_total 45
telemt_me_single_endpoint_outage_reconnect_attempt_total 79
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 79
telemt_me_single_endpoint_shadow_rotate_total 188
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_desync_total 12492
telemt_desync_full_logged_total 3198
telemt_desync_suppressed_total 9294
telemt_desync_frames_bucket_total{bucket="1_2"} 2164
telemt_desync_frames_bucket_total{bucket="3_10"} 5086
telemt_desync_frames_bucket_total{bucket="gt_10"} 5242
telemt_pool_swap_total 22
telemt_pool_force_close_total 922
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 353
telemt_me_draining_writers_reap_progress_total 6366
telemt_me_writer_removed_unexpected_total 563
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1129
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5764
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 650
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 272
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 5444
telemt_me_writer_teardown_success_total{mode="normal"} 6893
telemt_me_writer_teardown_noop_total 6371
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 10758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 12002
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 12436
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 12926
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 13163
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 13256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 13264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 13264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 13264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 13264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 13264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 13264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 13264
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 30.118668
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 13264
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 353
telemt_me_refill_failed_total 284
telemt_me_writer_restored_same_endpoint_total 447
telemt_me_writer_restored_fallback_total 3
telemt_me_no_writer_failfast_total 86
telemt_me_async_recovery_trigger_total 3059
telemt_me_writer_removed_unexpected_minus_restored_total 113
telemt_user_connections_total{user="hello"} 8289941
telemt_user_connections_current{user="hello"} 2176
telemt_user_octets_from_client{user="hello"} 51276653882 (47.76 GB)
telemt_user_octets_to_client{user="hello"} 245459384264 (228.60 GB)
telemt_user_msgs_from_client{user="hello"} 48912
telemt_user_msgs_to_client{user="hello"} 39981
telemt_user_unique_ips_current{user="hello"} 816
telemt_user_unique_ips_recent_window{user="hello"} 290
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 153712.3 (42h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10063899
telemt_connections_bad_total 836466
telemt_connections_current 1951
telemt_connections_me_current 1951
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 220723
telemt_upstream_connect_attempt_total 91947
telemt_upstream_connect_success_total 90999
telemt_upstream_connect_fail_total 808
telemt_upstream_connect_attempts_per_request{bucket="1"} 91807
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 56037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33490
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1264
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 808
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71581
telemt_me_reconnect_success_total 2557
telemt_me_reader_eof_total 2268
telemt_me_idle_close_by_peer_total 2267
telemt_me_route_drop_no_conn_total 5017714
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7948338
telemt_me_endpoint_quarantine_total 1026
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1143
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 86
telemt_desync_total 41109
telemt_desync_full_logged_total 14057
telemt_desync_suppressed_total 27052
telemt_desync_frames_bucket_total{bucket="1_2"} 8353
telemt_desync_frames_bucket_total{bucket="3_10"} 15963
telemt_desync_frames_bucket_total{bucket="gt_10"} 16793
telemt_pool_swap_total 156
telemt_pool_force_close_total 4652
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 570
telemt_me_draining_writers_reap_progress_total 52209
telemt_me_writer_removed_unexpected_total 2314
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5583
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48958
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3997
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 655
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47557
telemt_me_writer_teardown_success_total{mode="normal"} 54541
telemt_me_writer_teardown_noop_total 52210
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 104840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 106059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 106437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 106707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 106741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 106744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 106744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 106747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 106751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 106751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 106751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 106751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 106751
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.171911
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 106751
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 570
telemt_me_refill_failed_total 4258
telemt_me_writer_restored_same_endpoint_total 2154
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 118
telemt_user_connections_total{user="hello"} 7948604
telemt_user_connections_current{user="hello"} 1951
telemt_user_octets_from_client{user="hello"} 180564031603 (168.16 GB)
telemt_user_octets_to_client{user="hello"} 2987475255597 (2.72 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 813
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 90548.3 (25h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10443565
telemt_connections_bad_total 382073
telemt_connections_current 1551
telemt_connections_me_current 1551
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4410765
telemt_upstream_connect_attempt_total 43869
telemt_upstream_connect_success_total 43545
telemt_upstream_connect_fail_total 315
telemt_upstream_connect_attempts_per_request{bucket="1"} 43860
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18714
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 134
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 315
telemt_me_reconnect_attempts_total 48008
telemt_me_reconnect_success_total 1488
telemt_me_reader_eof_total 1150
telemt_me_idle_close_by_peer_total 1149
telemt_me_route_drop_no_conn_total 3875772
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5005844
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 680
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 27287
telemt_desync_full_logged_total 9205
telemt_desync_suppressed_total 18082
telemt_desync_frames_bucket_total{bucket="1_2"} 5513
telemt_desync_frames_bucket_total{bucket="3_10"} 10789
telemt_desync_frames_bucket_total{bucket="gt_10"} 10985
telemt_pool_swap_total 95
telemt_pool_force_close_total 2956
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 308
telemt_me_draining_writers_reap_progress_total 31043
telemt_me_writer_removed_unexpected_total 1214
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2814
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29472
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2537
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 419
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28087
telemt_me_writer_teardown_success_total{mode="normal"} 32286
telemt_me_writer_teardown_noop_total 31050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63336
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63336
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.604648
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63336
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 308
telemt_me_refill_failed_total 2704
telemt_me_writer_restored_same_endpoint_total 1323
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4999560
telemt_user_connections_current{user="hello"} 1551
telemt_user_octets_from_client{user="hello"} 108125789144 (100.70 GB)
telemt_user_octets_to_client{user="hello"} 1881283332646 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 615
telemt_user_unique_ips_recent_window{user="hello"} 211
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 71519.6 (19h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 914475
telemt_connections_bad_total 11847
telemt_connections_current 1108
telemt_connections_me_current 1108
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18072
telemt_upstream_connect_attempt_total 35542
telemt_upstream_connect_success_total 35452
telemt_upstream_connect_fail_total 74
telemt_upstream_connect_attempts_per_request{bucket="1"} 35526
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16151
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 487
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 74
telemt_me_reconnect_attempts_total 1608
telemt_me_reconnect_success_total 675
telemt_me_reader_eof_total 652
telemt_me_idle_close_by_peer_total 652
telemt_me_route_drop_no_conn_total 313265
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 813319
telemt_me_endpoint_quarantine_total 627
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 595
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_desync_total 4492
telemt_desync_full_logged_total 1371
telemt_desync_suppressed_total 3121
telemt_desync_frames_bucket_total{bucket="1_2"} 1060
telemt_desync_frames_bucket_total{bucket="3_10"} 1779
telemt_desync_frames_bucket_total{bucket="gt_10"} 1653
telemt_pool_swap_total 76
telemt_pool_force_close_total 1908
telemt_me_writer_close_signal_drop_total 109
telemt_me_draining_writers_reap_progress_total 29342
telemt_me_writer_removed_unexpected_total 630
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2264
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27732
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1830
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 78
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27434
telemt_me_writer_teardown_success_total{mode="normal"} 29996
telemt_me_writer_teardown_noop_total 29344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59340
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59340
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.462246
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59340
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 109
telemt_me_refill_failed_total 51
telemt_me_writer_restored_same_endpoint_total 577
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 814395
telemt_user_connections_current{user="hello"} 1108
telemt_user_octets_from_client{user="hello"} 14977967365 (13.95 GB)
telemt_user_octets_to_client{user="hello"} 373798389579 (348.13 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 153717.0 (42h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12357507
telemt_connections_bad_total 1438405
telemt_connections_current 2232
telemt_connections_me_current 2232
telemt_handshake_timeouts_total 338145
telemt_upstream_connect_attempt_total 57491
telemt_upstream_connect_success_total 57265
telemt_upstream_connect_fail_total 176
telemt_upstream_connect_attempts_per_request{bucket="1"} 57441
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28216
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28987
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 176
telemt_me_reconnect_attempts_total 2256
telemt_me_reconnect_success_total 1199
telemt_me_reader_eof_total 1164
telemt_me_idle_close_by_peer_total 1164
telemt_me_route_drop_no_conn_total 4126604
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9333413
telemt_me_endpoint_quarantine_total 1041
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1147
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 38257
telemt_desync_full_logged_total 12491
telemt_desync_suppressed_total 25766
telemt_desync_frames_bucket_total{bucket="1_2"} 9107
telemt_desync_frames_bucket_total{bucket="3_10"} 14178
telemt_desync_frames_bucket_total{bucket="gt_10"} 14972
telemt_pool_swap_total 170
telemt_pool_force_close_total 4709
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 606
telemt_me_draining_writers_reap_progress_total 51783
telemt_me_writer_removed_unexpected_total 1118
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4256
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 48677
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4536
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 173
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 47074
telemt_me_writer_teardown_success_total{mode="normal"} 52933
telemt_me_writer_teardown_noop_total 51785
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102399
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103942
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104705
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104718
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.804507
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104718
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 606
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 1049
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 9302837
telemt_user_connections_current{user="hello"} 2232
telemt_user_octets_from_client{user="hello"} 180141324156 (167.77 GB)
telemt_user_octets_to_client{user="hello"} 4110087968088 (3.74 TB)
telemt_user_unique_ips_current{user="hello"} 825
telemt_user_unique_ips_recent_window{user="hello"} 255
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 153713.4 (42h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10699374
telemt_connections_bad_total 1194591
telemt_connections_current 1764
telemt_connections_me_current 1764
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 276157
telemt_upstream_connect_attempt_total 83315
telemt_upstream_connect_success_total 82695
telemt_upstream_connect_fail_total 536
telemt_upstream_connect_attempts_per_request{bucket="1"} 83231
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 45570
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 34192
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2024
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 536
telemt_me_reconnect_attempts_total 8807
telemt_me_reconnect_success_total 2025
telemt_me_reader_eof_total 1891
telemt_me_idle_close_by_peer_total 1891
telemt_me_seq_mismatch_total 72
telemt_me_route_drop_no_conn_total 5375451
telemt_me_route_drop_channel_closed_total 344
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8267666
telemt_me_endpoint_quarantine_total 1165
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 38
telemt_me_single_endpoint_outage_exit_total 38
telemt_me_single_endpoint_outage_reconnect_attempt_total 38
telemt_me_single_endpoint_outage_reconnect_success_total 36
telemt_me_single_endpoint_quarantine_bypass_total 38
telemt_me_single_endpoint_shadow_rotate_total 1151
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 37884
telemt_desync_full_logged_total 12224
telemt_desync_suppressed_total 25660
telemt_desync_frames_bucket_total{bucket="1_2"} 9433
telemt_desync_frames_bucket_total{bucket="3_10"} 14124
telemt_desync_frames_bucket_total{bucket="gt_10"} 14327
telemt_pool_swap_total 162
telemt_pool_force_close_total 4556
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 596
telemt_me_draining_writers_reap_progress_total 51277
telemt_me_writer_removed_unexpected_total 1916
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5353
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47907
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4117
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 439
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 46721
telemt_me_writer_teardown_success_total{mode="normal"} 53260
telemt_me_writer_teardown_noop_total 51282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 102078
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 103695
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 104188
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 104492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 104542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 104542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 104542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 104542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 104542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 104542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 104542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 104542
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 104542
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 16.162798
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 104542
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 596
telemt_me_refill_failed_total 348
telemt_me_writer_restored_same_endpoint_total 1648
telemt_me_writer_restored_fallback_total 98
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 170
telemt_user_connections_total{user="hello"} 8273766
telemt_user_connections_current{user="hello"} 1764
telemt_user_octets_from_client{user="hello"} 145492669905 (135.50 GB)
telemt_user_octets_to_client{user="hello"} 3155442244587 (2.87 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 694
telemt_user_unique_ips_recent_window{user="hello"} 218
```