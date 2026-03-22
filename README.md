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

# Server Metrics 2026-03-22 02:56:18 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 20995.6 (5h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307312
telemt_connections_bad_total 20775
telemt_connections_current 839
telemt_connections_me_current 839
telemt_handshake_timeouts_total 17786
telemt_upstream_connect_attempt_total 8831
telemt_upstream_connect_success_total 8830
telemt_upstream_connect_attempts_per_request{bucket="1"} 8830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5642
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 262
telemt_me_reconnect_success_total 138
telemt_me_reader_eof_total 133
telemt_me_idle_close_by_peer_total 133
telemt_me_route_drop_no_conn_total 58733
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252576
telemt_me_endpoint_quarantine_total 174
telemt_me_single_endpoint_shadow_rotate_total 179
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 2226
telemt_desync_full_logged_total 605
telemt_desync_suppressed_total 1621
telemt_desync_frames_bucket_total{bucket="1_2"} 743
telemt_desync_frames_bucket_total{bucket="3_10"} 829
telemt_desync_frames_bucket_total{bucket="gt_10"} 654
telemt_pool_swap_total 23
telemt_pool_force_close_total 604
telemt_me_writer_close_signal_drop_total 40
telemt_me_draining_writers_reap_progress_total 7972
telemt_me_writer_removed_unexpected_total 133
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 540
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7555
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 599
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7368
telemt_me_writer_teardown_success_total{mode="normal"} 8095
telemt_me_writer_teardown_noop_total 7973
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 15601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 15879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 15975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16068
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16068
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.924801
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16068
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 40
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 124
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 252064
telemt_user_connections_current{user="hello"} 839
telemt_user_octets_from_client{user="hello"} 2876496528 (2.68 GB)
telemt_user_octets_to_client{user="hello"} 92244450344 (85.91 GB)
telemt_user_unique_ips_current{user="hello"} 370
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 34362.0 (9h 32m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 801023
telemt_connections_bad_total 50310
telemt_connections_current 824
telemt_connections_me_current 824
telemt_handshake_timeouts_total 29592
telemt_upstream_connect_attempt_total 16027
telemt_upstream_connect_success_total 15774
telemt_upstream_connect_fail_total 230
telemt_upstream_connect_attempts_per_request{bucket="1"} 16004
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6942
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 230
telemt_me_reconnect_attempts_total 1360
telemt_me_reconnect_success_total 498
telemt_me_reader_eof_total 438
telemt_me_idle_close_by_peer_total 438
telemt_me_route_drop_no_conn_total 342503
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 632930
telemt_me_endpoint_quarantine_total 330
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 19
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 19
telemt_me_single_endpoint_shadow_rotate_total 276
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 35
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 2735
telemt_desync_full_logged_total 1572
telemt_desync_suppressed_total 1163
telemt_desync_frames_bucket_total{bucket="1_2"} 583
telemt_desync_frames_bucket_total{bucket="3_10"} 1041
telemt_desync_frames_bucket_total{bucket="gt_10"} 1111
telemt_pool_swap_total 37
telemt_pool_force_close_total 983
telemt_me_writer_close_signal_drop_total 66
telemt_me_draining_writers_reap_progress_total 14194
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1192
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 13427
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 961
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 22
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13211
telemt_me_writer_teardown_success_total{mode="normal"} 14619
telemt_me_writer_teardown_noop_total 14194
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 28285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28707
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28811
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28813
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28813
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.748707
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28813
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 66
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 365
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 632025
telemt_user_connections_current{user="hello"} 824
telemt_user_octets_from_client{user="hello"} 10283349052 (9.58 GB)
telemt_user_octets_to_client{user="hello"} 225288591476 (209.82 GB)
telemt_user_unique_ips_current{user="hello"} 532
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 109221.9 (30h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7773754
telemt_connections_bad_total 632244
telemt_connections_current 1555
telemt_connections_me_current 1555
telemt_handshake_timeouts_total 255361
telemt_upstream_connect_attempt_total 40579
telemt_upstream_connect_success_total 40504
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 40511
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21995
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 171
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1578
telemt_me_reconnect_success_total 817
telemt_me_reader_eof_total 826
telemt_me_idle_close_by_peer_total 826
telemt_me_route_drop_no_conn_total 4539967
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6288495
telemt_me_endpoint_quarantine_total 702
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 815
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
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
telemt_desync_total 26515
telemt_desync_full_logged_total 8775
telemt_desync_suppressed_total 17740
telemt_desync_frames_bucket_total{bucket="1_2"} 5717
telemt_desync_frames_bucket_total{bucket="3_10"} 10358
telemt_desync_frames_bucket_total{bucket="gt_10"} 10440
telemt_pool_swap_total 118
telemt_pool_force_close_total 3912
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 605
telemt_me_draining_writers_reap_progress_total 37050
telemt_me_writer_removed_unexpected_total 795
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3094
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34285
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3673
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33138
telemt_me_writer_teardown_success_total{mode="normal"} 37379
telemt_me_writer_teardown_noop_total 37094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71045
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 73617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74473
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74473
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 160.773858
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74473
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 605
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 727
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 63
telemt_user_connections_total{user="hello"} 6280596
telemt_user_connections_current{user="hello"} 1555
telemt_user_octets_from_client{user="hello"} 106513872684 (99.20 GB)
telemt_user_octets_to_client{user="hello"} 2090637335024 (1.90 TB)
telemt_user_unique_ips_current{user="hello"} 770
telemt_user_unique_ips_recent_window{user="hello"} 208
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 109223.2 (30h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6418955
telemt_connections_bad_total 588026
telemt_connections_current 1576
telemt_connections_me_current 1576
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 212567
telemt_upstream_connect_attempt_total 44623
telemt_upstream_connect_success_total 44233
telemt_upstream_connect_fail_total 193
telemt_upstream_connect_attempts_per_request{bucket="1"} 44426
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 557
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 193
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1945
telemt_me_reconnect_success_total 875
telemt_me_reader_eof_total 847
telemt_me_idle_close_by_peer_total 847
telemt_me_route_drop_no_conn_total 2260661
telemt_me_route_drop_channel_closed_total 263
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4795235
telemt_me_endpoint_quarantine_total 687
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 841
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 22643
telemt_desync_full_logged_total 7714
telemt_desync_suppressed_total 14929
telemt_desync_frames_bucket_total{bucket="1_2"} 5449
telemt_desync_frames_bucket_total{bucket="3_10"} 8795
telemt_desync_frames_bucket_total{bucket="gt_10"} 8399
telemt_pool_swap_total 119
telemt_pool_force_close_total 3544
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 363
telemt_me_draining_writers_reap_progress_total 35591
telemt_me_writer_removed_unexpected_total 832
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2966
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33394
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3331
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32047
telemt_me_writer_teardown_success_total{mode="normal"} 36360
telemt_me_writer_teardown_noop_total 35597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71752
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71957
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.321572
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71957
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 363
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 766
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4717373
telemt_user_connections_current{user="hello"} 1576
telemt_user_octets_from_client{user="hello"} 140556200549 (130.90 GB)
telemt_user_octets_to_client{user="hello"} 2226452729351 (2.02 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 743
telemt_user_unique_ips_recent_window{user="hello"} 182
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 109188.7 (30h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6297828
telemt_connections_bad_total 548704
telemt_connections_current 1444
telemt_connections_me_current 1444
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 203925
telemt_upstream_connect_attempt_total 50736
telemt_upstream_connect_success_total 50364
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 50500
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25704
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23102
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 484
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1074
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 2071
telemt_me_reconnect_success_total 913
telemt_me_reader_eof_total 858
telemt_me_idle_close_by_peer_total 858
telemt_me_route_drop_no_conn_total 2154337
telemt_me_route_drop_channel_closed_total 121
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4684190
telemt_me_endpoint_quarantine_total 769
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 816
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 41
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
telemt_desync_total 22566
telemt_desync_full_logged_total 7589
telemt_desync_suppressed_total 14977
telemt_desync_frames_bucket_total{bucket="1_2"} 5504
telemt_desync_frames_bucket_total{bucket="3_10"} 8646
telemt_desync_frames_bucket_total{bucket="gt_10"} 8416
telemt_pool_swap_total 118
telemt_pool_force_close_total 3426
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 386
telemt_me_draining_writers_reap_progress_total 36696
telemt_me_writer_removed_unexpected_total 830
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3040
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34500
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3211
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 33270
telemt_me_writer_teardown_success_total{mode="normal"} 37540
telemt_me_writer_teardown_noop_total 36708
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 73035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 73497
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 73988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74248
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 27.068016
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74248
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 386
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 791
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 4679711
telemt_user_connections_current{user="hello"} 1444
telemt_user_octets_from_client{user="hello"} 133918524727 (124.72 GB)
telemt_user_octets_to_client{user="hello"} 2144523251619 (1.95 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 164
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 109226.7 (30h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20453588
telemt_connections_bad_total 1634021
telemt_connections_current 2198
telemt_connections_me_current 2198
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 610019
telemt_upstream_connect_attempt_total 199626
telemt_upstream_connect_success_total 181525
telemt_upstream_connect_fail_total 16340
telemt_upstream_connect_attempts_per_request{bucket="1"} 197865
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 128413
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 42962
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8929
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16340
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64942
telemt_me_reconnect_success_total 2334
telemt_me_reader_eof_total 1464
telemt_me_idle_close_by_peer_total 1463
telemt_me_route_drop_no_conn_total 39514285
telemt_me_route_drop_channel_closed_total 124
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16522431
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 859
telemt_me_single_endpoint_outage_enter_total 135
telemt_me_single_endpoint_outage_exit_total 135
telemt_me_single_endpoint_outage_reconnect_attempt_total 285
telemt_me_single_endpoint_outage_reconnect_success_total 70
telemt_me_single_endpoint_quarantine_bypass_total 285
telemt_me_single_endpoint_shadow_rotate_total 856
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 64
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
telemt_desync_total 31994
telemt_desync_full_logged_total 9607
telemt_desync_suppressed_total 22387
telemt_desync_frames_bucket_total{bucket="1_2"} 6931
telemt_desync_frames_bucket_total{bucket="3_10"} 14207
telemt_desync_frames_bucket_total{bucket="gt_10"} 10856
telemt_pool_swap_total 113
telemt_pool_force_close_total 3656
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 798
telemt_me_draining_writers_reap_progress_total 34305
telemt_me_writer_removed_unexpected_total 2162
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4626
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31582
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 24
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3132
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 524
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30649
telemt_me_writer_teardown_success_total{mode="normal"} 36208
telemt_me_writer_teardown_noop_total 34332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 63709
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66200
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70096
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70540
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 215.158640
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70540
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 798
telemt_me_refill_failed_total 3804
telemt_me_writer_restored_same_endpoint_total 1599
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 542
telemt_user_connections_total{user="hello"} 16655572
telemt_user_connections_current{user="hello"} 2198
telemt_user_octets_from_client{user="hello"} 221675550528 (206.45 GB)
telemt_user_octets_to_client{user="hello"} 1208597107409 (1.10 TB)
telemt_user_msgs_from_client{user="hello"} 395497
telemt_user_msgs_to_client{user="hello"} 785476
telemt_user_unique_ips_current{user="hello"} 1029
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 109194.0 (30h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6048449
telemt_connections_bad_total 570368
telemt_connections_current 1088
telemt_connections_me_current 1088
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 127067
telemt_upstream_connect_attempt_total 59370
telemt_upstream_connect_success_total 58681
telemt_upstream_connect_fail_total 588
telemt_upstream_connect_attempts_per_request{bucket="1"} 59269
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24063
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 351
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 588
telemt_me_reconnect_attempts_total 69673
telemt_me_reconnect_success_total 1804
telemt_me_reader_eof_total 1583
telemt_me_idle_close_by_peer_total 1582
telemt_me_route_drop_no_conn_total 2392333
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4714327
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 828
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 23437
telemt_desync_full_logged_total 8259
telemt_desync_suppressed_total 15178
telemt_desync_frames_bucket_total{bucket="1_2"} 4476
telemt_desync_frames_bucket_total{bucket="3_10"} 9077
telemt_desync_frames_bucket_total{bucket="gt_10"} 9884
telemt_pool_swap_total 113
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 396
telemt_me_draining_writers_reap_progress_total 38512
telemt_me_writer_removed_unexpected_total 1621
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3961
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36203
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2845
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35266
telemt_me_writer_teardown_success_total{mode="normal"} 40164
telemt_me_writer_teardown_noop_total 38513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 78246
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 78525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78677
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78677
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.129894
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78677
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 396
telemt_me_refill_failed_total 4206
telemt_me_writer_restored_same_endpoint_total 1513
telemt_me_writer_restored_fallback_total 35
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 73
telemt_user_connections_total{user="hello"} 4707102
telemt_user_connections_current{user="hello"} 1088
telemt_user_octets_from_client{user="hello"} 124897458580 (116.32 GB)
telemt_user_octets_to_client{user="hello"} 1919075573506 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 554
telemt_user_unique_ips_recent_window{user="hello"} 147
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 46030.0 (12h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3957798
telemt_connections_bad_total 145476
telemt_connections_current 1704
telemt_connections_me_current 1704
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1612343
telemt_upstream_connect_attempt_total 27957
telemt_upstream_connect_success_total 27778
telemt_upstream_connect_fail_total 172
telemt_upstream_connect_attempts_per_request{bucket="1"} 27950
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17466
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10236
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 76
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 172
telemt_me_reconnect_attempts_total 45825
telemt_me_reconnect_success_total 972
telemt_me_reader_eof_total 654
telemt_me_idle_close_by_peer_total 654
telemt_me_route_drop_no_conn_total 1024579
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1939246
telemt_me_endpoint_quarantine_total 344
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 50
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 50
telemt_me_single_endpoint_shadow_rotate_total 353
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10519
telemt_desync_full_logged_total 3625
telemt_desync_suppressed_total 6894
telemt_desync_frames_bucket_total{bucket="1_2"} 1900
telemt_desync_frames_bucket_total{bucket="3_10"} 4032
telemt_desync_frames_bucket_total{bucket="gt_10"} 4587
telemt_pool_swap_total 50
telemt_pool_force_close_total 1492
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 135
telemt_me_draining_writers_reap_progress_total 16955
telemt_me_writer_removed_unexpected_total 728
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1539
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 16170
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1286
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 15463
telemt_me_writer_teardown_success_total{mode="normal"} 17709
telemt_me_writer_teardown_noop_total 16957
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 34428
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 34560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 34666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 34666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 34666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 34666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 34666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 34666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 34666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 34666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 34666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 34666
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.443999
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 34666
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 135
telemt_me_refill_failed_total 2606
telemt_me_writer_restored_same_endpoint_total 871
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1942845
telemt_user_connections_current{user="hello"} 1704
telemt_user_octets_from_client{user="hello"} 54259903916 (50.53 GB)
telemt_user_octets_to_client{user="hello"} 824641146034 (768.01 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 894
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 27001.1 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 199725
telemt_connections_bad_total 1735
telemt_connections_current 329
telemt_connections_me_current 329
telemt_handshake_timeouts_total 5497
telemt_upstream_connect_attempt_total 13011
telemt_upstream_connect_success_total 12979
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 13009
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7432
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 79
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_reconnect_attempts_total 292
telemt_me_reconnect_success_total 170
telemt_me_reader_eof_total 175
telemt_me_idle_close_by_peer_total 175
telemt_me_route_drop_no_conn_total 55074
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 176045
telemt_me_endpoint_quarantine_total 262
telemt_me_single_endpoint_shadow_rotate_total 233
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 4
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
telemt_desync_total 1031
telemt_desync_full_logged_total 261
telemt_desync_suppressed_total 770
telemt_desync_frames_bucket_total{bucket="1_2"} 390
telemt_desync_frames_bucket_total{bucket="3_10"} 384
telemt_desync_frames_bucket_total{bucket="gt_10"} 257
telemt_pool_swap_total 29
telemt_pool_force_close_total 647
telemt_me_writer_close_signal_drop_total 23
telemt_me_draining_writers_reap_progress_total 11744
telemt_me_writer_removed_unexpected_total 168
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 753
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11166
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 645
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11097
telemt_me_writer_teardown_success_total{mode="normal"} 11919
telemt_me_writer_teardown_noop_total 11744
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 23467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 23635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 23653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 23663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 23663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 23663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 23663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 23663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 23663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 23663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 23663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 23663
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 23663
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.986372
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 23663
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 23
telemt_me_refill_failed_total 7
telemt_me_writer_restored_same_endpoint_total 154
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 175730
telemt_user_connections_current{user="hello"} 329
telemt_user_octets_from_client{user="hello"} 3116383772 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 108598062888 (101.14 GB)
telemt_user_unique_ips_current{user="hello"} 149
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 109198.5 (30h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7365736
telemt_connections_bad_total 743075
telemt_connections_current 1791
telemt_connections_me_current 1791
telemt_handshake_timeouts_total 209783
telemt_upstream_connect_attempt_total 42853
telemt_upstream_connect_success_total 42696
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 42816
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21160
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21495
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_reconnect_attempts_total 1588
telemt_me_reconnect_success_total 853
telemt_me_reader_eof_total 836
telemt_me_idle_close_by_peer_total 836
telemt_me_route_drop_no_conn_total 2130385
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5499016
telemt_me_endpoint_quarantine_total 769
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 842
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_desync_total 21572
telemt_desync_full_logged_total 7069
telemt_desync_suppressed_total 14503
telemt_desync_frames_bucket_total{bucket="1_2"} 5422
telemt_desync_frames_bucket_total{bucket="3_10"} 7810
telemt_desync_frames_bucket_total{bucket="gt_10"} 8340
telemt_pool_swap_total 121
telemt_pool_force_close_total 3236
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 390
telemt_me_draining_writers_reap_progress_total 38657
telemt_me_writer_removed_unexpected_total 807
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3036
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36447
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3148
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35421
telemt_me_writer_teardown_success_total{mode="normal"} 39483
telemt_me_writer_teardown_noop_total 38659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 76778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77676
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77854
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78054
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 78142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 78142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 78142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 78142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 78142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 78142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 78142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 78142
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 78142
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.673266
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 78142
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 390
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 763
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 5474025
telemt_user_connections_current{user="hello"} 1791
telemt_user_octets_from_client{user="hello"} 109757113820 (102.22 GB)
telemt_user_octets_to_client{user="hello"} 2550062853516 (2.32 TB)
telemt_user_unique_ips_current{user="hello"} 755
telemt_user_unique_ips_recent_window{user="hello"} 173
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 109195.2 (30h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6355578
telemt_connections_bad_total 628463
telemt_connections_current 1469
telemt_connections_me_current 1469
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 173457
telemt_upstream_connect_attempt_total 58661
telemt_upstream_connect_success_total 58221
telemt_upstream_connect_fail_total 381
telemt_upstream_connect_attempts_per_request{bucket="1"} 58602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33887
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23200
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 616
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 381
telemt_me_reconnect_attempts_total 5581
telemt_me_reconnect_success_total 1182
telemt_me_reader_eof_total 1068
telemt_me_idle_close_by_peer_total 1068
telemt_me_seq_mismatch_total 48
telemt_me_route_drop_no_conn_total 2183205
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4865809
telemt_me_endpoint_quarantine_total 863
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 28
telemt_me_single_endpoint_outage_reconnect_success_total 26
telemt_me_single_endpoint_quarantine_bypass_total 28
telemt_me_single_endpoint_shadow_rotate_total 837
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
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
telemt_desync_total 20189
telemt_desync_full_logged_total 6724
telemt_desync_suppressed_total 13465
telemt_desync_frames_bucket_total{bucket="1_2"} 5175
telemt_desync_frames_bucket_total{bucket="3_10"} 7360
telemt_desync_frames_bucket_total{bucket="gt_10"} 7654
telemt_pool_swap_total 119
telemt_pool_force_close_total 3195
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 382
telemt_me_draining_writers_reap_progress_total 37227
telemt_me_writer_removed_unexpected_total 1078
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3564
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34794
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2972
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34032
telemt_me_writer_teardown_success_total{mode="normal"} 38358
telemt_me_writer_teardown_noop_total 37231
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73946
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75589
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75589
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.091530
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75589
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 382
telemt_me_refill_failed_total 254
telemt_me_writer_restored_same_endpoint_total 924
telemt_me_writer_restored_fallback_total 64
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 90
telemt_user_connections_total{user="hello"} 4868801
telemt_user_connections_current{user="hello"} 1469
telemt_user_octets_from_client{user="hello"} 91882008421 (85.57 GB)
telemt_user_octets_to_client{user="hello"} 2079426262544 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 669
telemt_user_unique_ips_recent_window{user="hello"} 161
```