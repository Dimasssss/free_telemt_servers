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

# Server Metrics 2026-03-22 21:47:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 88858.8 (24h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3241750
telemt_connections_bad_total 238387
telemt_connections_current 855
telemt_connections_me_current 855
telemt_handshake_timeouts_total 103560
telemt_upstream_connect_attempt_total 32586
telemt_upstream_connect_success_total 32585
telemt_upstream_connect_attempts_per_request{bucket="1"} 32585
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21253
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 91
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 292
telemt_me_reconnect_attempts_total 1314
telemt_me_reconnect_success_total 544
telemt_me_reader_eof_total 556
telemt_me_idle_close_by_peer_total 556
telemt_me_route_drop_no_conn_total 2855689
telemt_me_route_drop_channel_closed_total 1189
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2729062
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 599
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 689
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 11796
telemt_desync_full_logged_total 3699
telemt_desync_suppressed_total 8097
telemt_desync_frames_bucket_total{bucket="1_2"} 3200
telemt_desync_frames_bucket_total{bucket="3_10"} 4302
telemt_desync_frames_bucket_total{bucket="gt_10"} 4294
telemt_pool_swap_total 98
telemt_pool_force_close_total 3048
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 608
telemt_me_draining_writers_reap_progress_total 29787
telemt_me_writer_removed_unexpected_total 540
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2163
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27863
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2993
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26739
telemt_me_writer_teardown_success_total{mode="normal"} 30026
telemt_me_writer_teardown_noop_total 29798
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47189
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49347
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59819
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59824
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 346.851445
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59824
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 608
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 484
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2718708
telemt_user_connections_current{user="hello"} 855
telemt_user_octets_from_client{user="hello"} 39406102280 (36.70 GB)
telemt_user_octets_to_client{user="hello"} 736088810620 (685.54 GB)
telemt_user_unique_ips_current{user="hello"} 398
telemt_user_unique_ips_recent_window{user="hello"} 315
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 102224.6 (28h 23m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3915270
telemt_connections_bad_total 348229
telemt_connections_current 549
telemt_connections_me_current 549
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99445
telemt_upstream_connect_attempt_total 61270
telemt_upstream_connect_success_total 60527
telemt_upstream_connect_fail_total 657
telemt_upstream_connect_attempts_per_request{bucket="1"} 61184
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33670
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26661
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 196
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 657
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 7024
telemt_me_reconnect_success_total 2762
telemt_me_reader_eof_total 2710
telemt_me_idle_close_by_peer_total 2710
telemt_me_route_drop_no_conn_total 3628304
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3120525
telemt_me_endpoint_quarantine_total 770
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 790
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_me_writers_active_current 91
telemt_desync_total 12681
telemt_desync_full_logged_total 7106
telemt_desync_suppressed_total 5575
telemt_desync_frames_bucket_total{bucket="1_2"} 2865
telemt_desync_frames_bucket_total{bucket="3_10"} 4977
telemt_desync_frames_bucket_total{bucket="gt_10"} 4839
telemt_pool_swap_total 95
telemt_pool_force_close_total 2879
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 40876
telemt_me_writer_removed_unexpected_total 2651
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4980
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38569
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37997
telemt_me_writer_teardown_success_total{mode="normal"} 43549
telemt_me_writer_teardown_noop_total 40877
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 82484
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 83715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 84040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 84348
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84424
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84426
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.393831
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84426
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 171
telemt_me_writer_restored_same_endpoint_total 2436
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 3131188
telemt_user_connections_current{user="hello"} 549
telemt_user_octets_from_client{user="hello"} 41546055659 (38.69 GB)
telemt_user_octets_to_client{user="hello"} 768366858854 (715.60 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 351
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 177084.5 (49h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16119353
telemt_connections_bad_total 1567182
telemt_connections_current 959
telemt_connections_me_current 959
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 395260
telemt_upstream_connect_attempt_total 78540
telemt_upstream_connect_success_total 78440
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 78457
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38916
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37821
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1696
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2852
telemt_me_reconnect_success_total 1484
telemt_me_reader_eof_total 1430
telemt_me_idle_close_by_peer_total 1428
telemt_me_route_drop_no_conn_total 14019344
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12846865
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1321
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 53052
telemt_desync_full_logged_total 16765
telemt_desync_suppressed_total 36287
telemt_desync_frames_bucket_total{bucket="1_2"} 11787
telemt_desync_frames_bucket_total{bucket="3_10"} 20657
telemt_desync_frames_bucket_total{bucket="gt_10"} 20608
telemt_pool_swap_total 191
telemt_pool_force_close_total 6416
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1037
telemt_me_draining_writers_reap_progress_total 58474
telemt_me_writer_removed_unexpected_total 1379
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5115
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 54008
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 45
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5946
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 52058
telemt_me_writer_teardown_success_total{mode="normal"} 59123
telemt_me_writer_teardown_noop_total 58527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 110264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114331
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115989
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 117040
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117611
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117641
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117642
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117648
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117650
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117650
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 315.898946
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117650
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1037
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1283
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12847165
telemt_user_connections_current{user="hello"} 959
telemt_user_octets_from_client{user="hello"} 189122033645 (176.13 GB)
telemt_user_octets_to_client{user="hello"} 3446132518723 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 451
telemt_user_unique_ips_recent_window{user="hello"} 121
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 177085.9 (49h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11699580
telemt_connections_bad_total 1191297
telemt_connections_current 833
telemt_connections_me_current 833
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343593
telemt_upstream_connect_attempt_total 93020
telemt_upstream_connect_success_total 91713
telemt_upstream_connect_fail_total 861
telemt_upstream_connect_attempts_per_request{bucket="1"} 92574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49926
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37809
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3790
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 861
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4286
telemt_me_reconnect_success_total 1793
telemt_me_reader_eof_total 1653
telemt_me_idle_close_by_peer_total 1653
telemt_me_route_drop_no_conn_total 4534377
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8708490
telemt_me_endpoint_quarantine_total 1133
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1344
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
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
telemt_me_writers_active_current 43
telemt_desync_total 38479
telemt_desync_full_logged_total 12944
telemt_desync_suppressed_total 25535
telemt_desync_frames_bucket_total{bucket="1_2"} 9495
telemt_desync_frames_bucket_total{bucket="3_10"} 14795
telemt_desync_frames_bucket_total{bucket="gt_10"} 14189
telemt_pool_swap_total 188
telemt_pool_force_close_total 5787
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 56826
telemt_me_writer_removed_unexpected_total 1689
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5247
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53118
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5275
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51039
telemt_me_writer_teardown_success_total{mode="normal"} 58365
telemt_me_writer_teardown_noop_total 56851
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 108504
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114032
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114791
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115206
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115208
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115214
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115216
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115216
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.222354
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115216
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1526
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8646369
telemt_user_connections_current{user="hello"} 833
telemt_user_octets_from_client{user="hello"} 216838450472 (201.95 GB)
telemt_user_octets_to_client{user="hello"} 3917461158631 (3.56 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 368
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 177050.9 (49h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10930766
telemt_connections_bad_total 949514
telemt_connections_current 675
telemt_connections_me_current 675
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344698
telemt_upstream_connect_attempt_total 76702
telemt_upstream_connect_success_total 75286
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 75483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36166
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1845
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2292
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 5396
telemt_me_reconnect_success_total 2198
telemt_me_reader_eof_total 1934
telemt_me_idle_close_by_peer_total 1933
telemt_me_route_drop_no_conn_total 5314427
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8272686
telemt_me_endpoint_quarantine_total 1219
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1298
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 67
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
telemt_desync_total 37840
telemt_desync_full_logged_total 12538
telemt_desync_suppressed_total 25302
telemt_desync_frames_bucket_total{bucket="1_2"} 9562
telemt_desync_frames_bucket_total{bucket="3_10"} 14473
telemt_desync_frames_bucket_total{bucket="gt_10"} 13805
telemt_pool_swap_total 185
telemt_pool_force_close_total 5722
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 724
telemt_me_draining_writers_reap_progress_total 56963
telemt_me_writer_removed_unexpected_total 2084
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5848
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53125
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5157
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51241
telemt_me_writer_teardown_success_total{mode="normal"} 58973
telemt_me_writer_teardown_noop_total 57034
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 110234
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112919
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113863
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115526
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115907
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115920
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115953
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115956
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 116007
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.227443
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 116007
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 724
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 1898
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8264695
telemt_user_connections_current{user="hello"} 675
telemt_user_octets_from_client{user="hello"} 191883787613 (178.71 GB)
telemt_user_octets_to_client{user="hello"} 3438269371561 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 304
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 47329.9 (13h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11023256
telemt_connections_bad_total 666755
telemt_connections_current 1340
telemt_connections_me_current 1340
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 247420
telemt_upstream_connect_attempt_total 50706
telemt_upstream_connect_success_total 48165
telemt_upstream_connect_fail_total 1735
telemt_upstream_connect_attempts_per_request{bucket="1"} 49900
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5986
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1735
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7008
telemt_me_reconnect_success_total 1029
telemt_me_reader_eof_total 639
telemt_me_idle_close_by_peer_total 638
telemt_me_route_drop_no_conn_total 25250718
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9155053
telemt_me_endpoint_quarantine_total 328
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 374
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 30
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
telemt_desync_total 15656
telemt_desync_full_logged_total 4138
telemt_desync_suppressed_total 11518
telemt_desync_frames_bucket_total{bucket="1_2"} 3001
telemt_desync_frames_bucket_total{bucket="3_10"} 6331
telemt_desync_frames_bucket_total{bucket="gt_10"} 6324
telemt_pool_swap_total 48
telemt_pool_force_close_total 1687
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 450
telemt_me_draining_writers_reap_progress_total 13877
telemt_me_writer_removed_unexpected_total 916
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2018
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12733
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1381
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12190
telemt_me_writer_teardown_success_total{mode="normal"} 14751
telemt_me_writer_teardown_noop_total 13896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24994
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26612
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 28102
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 28468
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28591
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28647
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28647
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.144457
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28647
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 450
telemt_me_refill_failed_total 325
telemt_me_writer_restored_same_endpoint_total 669
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 9179763
telemt_user_connections_current{user="hello"} 1340
telemt_user_octets_from_client{user="hello"} 85235535488 (79.38 GB)
telemt_user_octets_to_client{user="hello"} 552277891454 (514.35 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 525
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 177056.6 (49h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10843717
telemt_connections_bad_total 913183
telemt_connections_current 1143
telemt_connections_me_current 1143
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 238632
telemt_upstream_connect_attempt_total 105765
telemt_upstream_connect_success_total 104659
telemt_upstream_connect_fail_total 941
telemt_upstream_connect_attempts_per_request{bucket="1"} 105600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39742
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 941
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72596
telemt_me_reconnect_success_total 2929
telemt_me_reader_eof_total 2625
telemt_me_idle_close_by_peer_total 2623
telemt_me_route_drop_no_conn_total 5235037
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8570292
telemt_me_endpoint_quarantine_total 1161
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1327
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 51
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
telemt_me_writers_active_current 92
telemt_desync_total 45774
telemt_desync_full_logged_total 15646
telemt_desync_suppressed_total 30128
telemt_desync_frames_bucket_total{bucket="1_2"} 9279
telemt_desync_frames_bucket_total{bucket="3_10"} 17517
telemt_desync_frames_bucket_total{bucket="gt_10"} 18978
telemt_pool_swap_total 180
telemt_pool_force_close_total 5371
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 647
telemt_me_draining_writers_reap_progress_total 60949
telemt_me_writer_removed_unexpected_total 2660
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6444
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57194
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4641
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55578
telemt_me_writer_teardown_success_total{mode="normal"} 63638
telemt_me_writer_teardown_noop_total 60950
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 122461
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123852
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 124271
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 124544
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 124578
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 124581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 124581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 124584
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 124588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 124588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 124588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 124588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 124588
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.142918
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 124588
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 647
telemt_me_refill_failed_total 4291
telemt_me_writer_restored_same_endpoint_total 2475
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8573402
telemt_user_connections_current{user="hello"} 1143
telemt_user_octets_from_client{user="hello"} 193508487873 (180.22 GB)
telemt_user_octets_to_client{user="hello"} 3271011628800 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 538
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 113892.7 (31h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11474320
telemt_connections_bad_total 459541
telemt_connections_current 668
telemt_connections_me_current 668
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4700984
telemt_upstream_connect_attempt_total 53802
telemt_upstream_connect_success_total 53406
telemt_upstream_connect_fail_total 386
telemt_upstream_connect_attempts_per_request{bucket="1"} 53792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 29076
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 205
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 386
telemt_me_reconnect_attempts_total 48664
telemt_me_reconnect_success_total 1703
telemt_me_reader_eof_total 1365
telemt_me_idle_close_by_peer_total 1364
telemt_me_route_drop_no_conn_total 4066410
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5532829
telemt_me_endpoint_quarantine_total 742
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 863
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31066
telemt_desync_full_logged_total 10583
telemt_desync_suppressed_total 20483
telemt_desync_frames_bucket_total{bucket="1_2"} 6166
telemt_desync_frames_bucket_total{bucket="3_10"} 12279
telemt_desync_frames_bucket_total{bucket="gt_10"} 12621
telemt_pool_swap_total 120
telemt_pool_force_close_total 3641
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 364
telemt_me_draining_writers_reap_progress_total 39947
telemt_me_writer_removed_unexpected_total 1422
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3455
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37951
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3200
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36306
telemt_me_writer_teardown_success_total{mode="normal"} 41406
telemt_me_writer_teardown_noop_total 39954
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 81133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81360
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.623319
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81360
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 364
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1513
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5525491
telemt_user_connections_current{user="hello"} 668
telemt_user_octets_from_client{user="hello"} 118272146648 (110.15 GB)
telemt_user_octets_to_client{user="hello"} 2122617363510 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 298
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 94863.6 (26h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1433828
telemt_connections_bad_total 35406
telemt_connections_current 656
telemt_connections_me_current 656
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 27590
telemt_upstream_connect_attempt_total 44415
telemt_upstream_connect_success_total 44276
telemt_upstream_connect_fail_total 111
telemt_upstream_connect_attempts_per_request{bucket="1"} 44387
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19940
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23577
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 759
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 111
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2055
telemt_me_reconnect_success_total 840
telemt_me_reader_eof_total 823
telemt_me_idle_close_by_peer_total 823
telemt_me_route_drop_no_conn_total 497432
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1272663
telemt_me_endpoint_quarantine_total 765
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 782
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 46
telemt_desync_total 7942
telemt_desync_full_logged_total 2415
telemt_desync_suppressed_total 5527
telemt_desync_frames_bucket_total{bucket="1_2"} 1930
telemt_desync_frames_bucket_total{bucket="3_10"} 3064
telemt_desync_frames_bucket_total{bucket="gt_10"} 2948
telemt_pool_swap_total 102
telemt_pool_force_close_total 2658
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 37145
telemt_me_writer_removed_unexpected_total 792
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2935
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35036
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2570
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34487
telemt_me_writer_teardown_success_total{mode="normal"} 37971
telemt_me_writer_teardown_noop_total 37149
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74238
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 75083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 75120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 75120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 75120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 75120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 75120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 75120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 75120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 75120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 75120
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 75120
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.895790
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 75120
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 713
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1268606
telemt_user_connections_current{user="hello"} 656
telemt_user_octets_from_client{user="hello"} 24933951281 (23.22 GB)
telemt_user_octets_to_client{user="hello"} 537363853199 (500.46 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 248
telemt_user_unique_ips_recent_window{user="hello"} 72
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 177061.1 (49h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13178256
telemt_connections_bad_total 1561845
telemt_connections_current 1061
telemt_connections_me_current 1061
telemt_handshake_timeouts_total 379002
telemt_upstream_connect_attempt_total 67506
telemt_upstream_connect_success_total 67169
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 67370
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33296
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33771
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2639
telemt_me_reconnect_success_total 1379
telemt_me_reader_eof_total 1347
telemt_me_idle_close_by_peer_total 1347
telemt_me_route_drop_no_conn_total 4464168
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9959653
telemt_me_endpoint_quarantine_total 1210
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1327
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 42
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
telemt_me_writers_active_current 46
telemt_desync_total 41571
telemt_desync_full_logged_total 13554
telemt_desync_suppressed_total 28017
telemt_desync_frames_bucket_total{bucket="1_2"} 9995
telemt_desync_frames_bucket_total{bucket="3_10"} 15300
telemt_desync_frames_bucket_total{bucket="gt_10"} 16276
telemt_pool_swap_total 196
telemt_pool_force_close_total 5357
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 659
telemt_me_draining_writers_reap_progress_total 60882
telemt_me_writer_removed_unexpected_total 1296
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4932
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 57287
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5183
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55525
telemt_me_writer_teardown_success_total{mode="normal"} 62219
telemt_me_writer_teardown_noop_total 60884
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122211
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122970
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123090
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123103
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.569454
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123103
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 659
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1206
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 9926496
telemt_user_connections_current{user="hello"} 1061
telemt_user_octets_from_client{user="hello"} 193854927192 (180.54 GB)
telemt_user_octets_to_client{user="hello"} 4393369210548 (4.00 TB)
telemt_user_unique_ips_current{user="hello"} 387
telemt_user_unique_ips_recent_window{user="hello"} 105
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 177057.7 (49h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11462666
telemt_connections_bad_total 1305728
telemt_connections_current 796
telemt_connections_me_current 796
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 302042
telemt_upstream_connect_attempt_total 93992
telemt_upstream_connect_success_total 93150
telemt_upstream_connect_fail_total 635
telemt_upstream_connect_attempts_per_request{bucket="1"} 93785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39327
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2066
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 635
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 10047
telemt_me_reconnect_success_total 2423
telemt_me_reader_eof_total 2264
telemt_me_idle_close_by_peer_total 2263
telemt_me_seq_mismatch_total 83
telemt_me_route_drop_no_conn_total 5623834
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8859804
telemt_me_endpoint_quarantine_total 1359
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1329
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_active_current 48
telemt_desync_total 41162
telemt_desync_full_logged_total 13197
telemt_desync_suppressed_total 27965
telemt_desync_frames_bucket_total{bucket="1_2"} 10562
telemt_desync_frames_bucket_total{bucket="3_10"} 15155
telemt_desync_frames_bucket_total{bucket="gt_10"} 15445
telemt_pool_swap_total 186
telemt_pool_force_close_total 5152
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 647
telemt_me_draining_writers_reap_progress_total 60674
telemt_me_writer_removed_unexpected_total 2297
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6268
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56782
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4681
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55522
telemt_me_writer_teardown_success_total{mode="normal"} 63050
telemt_me_writer_teardown_noop_total 60679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123679
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123729
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.294256
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123729
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 647
telemt_me_refill_failed_total 394
telemt_me_writer_restored_same_endpoint_total 1967
telemt_me_writer_restored_fallback_total 115
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 8865256
telemt_user_connections_current{user="hello"} 796
telemt_user_octets_from_client{user="hello"} 156584052465 (145.83 GB)
telemt_user_octets_to_client{user="hello"} 3450395496103 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 358
telemt_user_unique_ips_recent_window{user="hello"} 96
```