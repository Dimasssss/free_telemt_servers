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

# Server Metrics 2026-03-22 00:53:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 13651.5 (3h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 203235
telemt_connections_bad_total 14134
telemt_connections_current 633
telemt_connections_me_current 633
telemt_handshake_timeouts_total 11618
telemt_upstream_connect_attempt_total 5635
telemt_upstream_connect_success_total 5634
telemt_upstream_connect_attempts_per_request{bucket="1"} 5634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3540
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 201
telemt_me_reconnect_success_total 96
telemt_me_reader_eof_total 92
telemt_me_idle_close_by_peer_total 92
telemt_me_route_drop_no_conn_total 39073
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 165674
telemt_me_endpoint_quarantine_total 105
telemt_me_single_endpoint_shadow_rotate_total 120
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 1305
telemt_desync_full_logged_total 361
telemt_desync_suppressed_total 944
telemt_desync_frames_bucket_total{bucket="1_2"} 379
telemt_desync_frames_bucket_total{bucket="3_10"} 461
telemt_desync_frames_bucket_total{bucket="gt_10"} 465
telemt_pool_swap_total 15
telemt_pool_force_close_total 374
telemt_me_writer_close_signal_drop_total 25
telemt_me_draining_writers_reap_progress_total 5009
telemt_me_writer_removed_unexpected_total 94
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 374
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4717
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 370
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4635
telemt_me_writer_teardown_success_total{mode="normal"} 5091
telemt_me_writer_teardown_noop_total 5010
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 9794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 9976
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 10030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 10075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 10099
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 10101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 10101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 10101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 10101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 10101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 10101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 10101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 10101
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.708268
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 10101
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 25
telemt_me_refill_failed_total 6
telemt_me_writer_restored_same_endpoint_total 88
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 165421
telemt_user_connections_current{user="hello"} 633
telemt_user_octets_from_client{user="hello"} 1863783028 (1.74 GB)
telemt_user_octets_to_client{user="hello"} 55797881852 (51.97 GB)
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 79
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 27017.8 (7h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 710999
telemt_connections_bad_total 40699
telemt_connections_current 631
telemt_connections_me_current 631
telemt_handshake_timeouts_total 26851
telemt_upstream_connect_attempt_total 11778
telemt_upstream_connect_success_total 11581
telemt_upstream_connect_fail_total 178
telemt_upstream_connect_attempts_per_request{bucket="1"} 11759
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6375
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 178
telemt_me_reconnect_attempts_total 1027
telemt_me_reconnect_success_total 347
telemt_me_reader_eof_total 301
telemt_me_idle_close_by_peer_total 301
telemt_me_route_drop_no_conn_total 331621
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 573740
telemt_me_endpoint_quarantine_total 242
telemt_me_single_endpoint_outage_enter_total 15
telemt_me_single_endpoint_outage_exit_total 15
telemt_me_single_endpoint_outage_reconnect_attempt_total 15
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 15
telemt_me_single_endpoint_shadow_rotate_total 217
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
telemt_me_writers_active_current 50
telemt_desync_total 2500
telemt_desync_full_logged_total 1432
telemt_desync_suppressed_total 1068
telemt_desync_frames_bucket_total{bucket="1_2"} 538
telemt_desync_frames_bucket_total{bucket="3_10"} 936
telemt_desync_frames_bucket_total{bucket="gt_10"} 1026
telemt_pool_swap_total 29
telemt_pool_force_close_total 794
telemt_me_writer_close_signal_drop_total 58
telemt_me_draining_writers_reap_progress_total 10381
telemt_me_writer_removed_unexpected_total 284
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 887
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 9782
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 787
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 9587
telemt_me_writer_teardown_success_total{mode="normal"} 10669
telemt_me_writer_teardown_noop_total 10381
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 20588
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 20858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 20944
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 21036
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 21048
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 21050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 21050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 21050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 21050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 21050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 21050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 21050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 21050
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.405544
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 21050
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 58
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 242
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 572895
telemt_user_connections_current{user="hello"} 631
telemt_user_octets_from_client{user="hello"} 9714762672 (9.05 GB)
telemt_user_octets_to_client{user="hello"} 202460588420 (188.56 GB)
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 85
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 101877.7 (28h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7545506
telemt_connections_bad_total 610735
telemt_connections_current 1710
telemt_connections_me_current 1710
telemt_handshake_timeouts_total 245854
telemt_upstream_connect_attempt_total 37189
telemt_upstream_connect_success_total 37117
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 37124
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16788
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20161
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 162
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1529
telemt_me_reconnect_success_total 765
telemt_me_reader_eof_total 776
telemt_me_idle_close_by_peer_total 776
telemt_me_route_drop_no_conn_total 4511328
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6138310
telemt_me_endpoint_quarantine_total 650
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 758
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
telemt_me_writers_active_current 44
telemt_desync_total 26074
telemt_desync_full_logged_total 8616
telemt_desync_suppressed_total 17458
telemt_desync_frames_bucket_total{bucket="1_2"} 5607
telemt_desync_frames_bucket_total{bucket="3_10"} 10170
telemt_desync_frames_bucket_total{bucket="gt_10"} 10297
telemt_pool_swap_total 110
telemt_pool_force_close_total 3662
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 581
telemt_me_draining_writers_reap_progress_total 33889
telemt_me_writer_removed_unexpected_total 746
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2857
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31337
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3423
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30227
telemt_me_writer_teardown_success_total{mode="normal"} 34194
telemt_me_writer_teardown_noop_total 33933
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62121
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 63906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64864
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67287
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68116
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68127
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68127
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 155.489709
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68127
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 581
telemt_me_refill_failed_total 40
telemt_me_writer_restored_same_endpoint_total 682
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 59
telemt_user_connections_total{user="hello"} 6130611
telemt_user_connections_current{user="hello"} 1710
telemt_user_octets_from_client{user="hello"} 105036384564 (97.82 GB)
telemt_user_octets_to_client{user="hello"} 2029662128172 (1.85 TB)
telemt_user_unique_ips_current{user="hello"} 897
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 101879.2 (28h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6210130
telemt_connections_bad_total 581133
telemt_connections_current 689
telemt_connections_me_current 689
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 205880
telemt_upstream_connect_attempt_total 41367
telemt_upstream_connect_success_total 40984
telemt_upstream_connect_fail_total 186
telemt_upstream_connect_attempts_per_request{bucket="1"} 41170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20453
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19943
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 186
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1884
telemt_me_reconnect_success_total 833
telemt_me_reader_eof_total 801
telemt_me_idle_close_by_peer_total 801
telemt_me_route_drop_no_conn_total 2210394
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4653382
telemt_me_endpoint_quarantine_total 628
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 778
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22241
telemt_desync_full_logged_total 7545
telemt_desync_suppressed_total 14696
telemt_desync_frames_bucket_total{bucket="1_2"} 5356
telemt_desync_frames_bucket_total{bucket="3_10"} 8620
telemt_desync_frames_bucket_total{bucket="gt_10"} 8265
telemt_pool_swap_total 111
telemt_pool_force_close_total 3343
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 352
telemt_me_draining_writers_reap_progress_total 32627
telemt_me_writer_removed_unexpected_total 788
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2783
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30567
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3130
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 213
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29284
telemt_me_writer_teardown_success_total{mode="normal"} 33350
telemt_me_writer_teardown_noop_total 32633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 62699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 64221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 64790
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 65367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65778
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65983
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65983
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.189467
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65983
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 352
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 725
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 4587238
telemt_user_connections_current{user="hello"} 689
telemt_user_octets_from_client{user="hello"} 138901796001 (129.36 GB)
telemt_user_octets_to_client{user="hello"} 2153307945475 (1.96 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 396
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 101843.1 (28h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6114052
telemt_connections_bad_total 542118
telemt_connections_current 1267
telemt_connections_me_current 1267
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 196048
telemt_upstream_connect_attempt_total 47659
telemt_upstream_connect_success_total 47330
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 47466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24558
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21325
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 392
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1055
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1899
telemt_me_reconnect_success_total 859
telemt_me_reader_eof_total 799
telemt_me_idle_close_by_peer_total 799
telemt_me_route_drop_no_conn_total 2117384
telemt_me_route_drop_channel_closed_total 111
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4558176
telemt_me_endpoint_quarantine_total 703
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 761
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
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
telemt_desync_total 22099
telemt_desync_full_logged_total 7389
telemt_desync_suppressed_total 14710
telemt_desync_frames_bucket_total{bucket="1_2"} 5400
telemt_desync_frames_bucket_total{bucket="3_10"} 8468
telemt_desync_frames_bucket_total{bucket="gt_10"} 8231
telemt_pool_swap_total 110
telemt_pool_force_close_total 3197
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 33948
telemt_me_writer_removed_unexpected_total 774
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2833
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31900
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2982
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30751
telemt_me_writer_teardown_success_total{mode="normal"} 34733
telemt_me_writer_teardown_noop_total 33959
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 66205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 67555
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 68442
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 68649
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 68674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 68692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 68692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 68692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 68692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 68692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 68692
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 68692
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.565554
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 68692
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 744
telemt_me_writer_restored_fallback_total 5
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 4558923
telemt_user_connections_current{user="hello"} 1267
telemt_user_octets_from_client{user="hello"} 132398756663 (123.31 GB)
telemt_user_octets_to_client{user="hello"} 2084135785659 (1.90 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 661
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 101882.4 (28h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20128988
telemt_connections_bad_total 1525311
telemt_connections_current 2011
telemt_connections_me_current 2011
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 586419
telemt_upstream_connect_attempt_total 190577
telemt_upstream_connect_success_total 172891
telemt_upstream_connect_fail_total 16050
telemt_upstream_connect_attempts_per_request{bucket="1"} 188941
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121983
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40797
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8890
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16050
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64465
telemt_me_reconnect_success_total 2202
telemt_me_reader_eof_total 1384
telemt_me_idle_close_by_peer_total 1383
telemt_me_route_drop_no_conn_total 39471431
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16345056
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 125
telemt_me_single_endpoint_outage_exit_total 125
telemt_me_single_endpoint_outage_reconnect_attempt_total 261
telemt_me_single_endpoint_outage_reconnect_success_total 64
telemt_me_single_endpoint_quarantine_bypass_total 261
telemt_me_single_endpoint_shadow_rotate_total 796
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 58
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 41
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 42
telemt_desync_total 31603
telemt_desync_full_logged_total 9429
telemt_desync_suppressed_total 22174
telemt_desync_frames_bucket_total{bucket="1_2"} 6866
telemt_desync_frames_bucket_total{bucket="3_10"} 14015
telemt_desync_frames_bucket_total{bucket="gt_10"} 10722
telemt_pool_swap_total 105
telemt_pool_force_close_total 3441
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 767
telemt_me_draining_writers_reap_progress_total 31731
telemt_me_writer_removed_unexpected_total 2043
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4305
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29205
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2919
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 522
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28290
telemt_me_writer_teardown_success_total{mode="normal"} 33510
telemt_me_writer_teardown_noop_total 31757
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58690
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 61053
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62304
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 64831
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 65166
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 65248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 65250
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 65253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 65258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 65258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 65262
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 65267
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.409526
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 65267
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 767
telemt_me_refill_failed_total 3792
telemt_me_writer_restored_same_endpoint_total 1527
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 495
telemt_user_connections_total{user="hello"} 16472676
telemt_user_connections_current{user="hello"} 2011
telemt_user_octets_from_client{user="hello"} 197404003076 (183.85 GB)
telemt_user_octets_to_client{user="hello"} 1151079341098 (1.05 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 965
telemt_user_unique_ips_recent_window{user="hello"} 230
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 101849.9 (28h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5893734
telemt_connections_bad_total 554874
telemt_connections_current 1446
telemt_connections_me_current 1446
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 122539
telemt_upstream_connect_attempt_total 55879
telemt_upstream_connect_success_total 55223
telemt_upstream_connect_fail_total 563
telemt_upstream_connect_attempts_per_request{bucket="1"} 55786
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22232
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 563
telemt_me_reconnect_attempts_total 69420
telemt_me_reconnect_success_total 1731
telemt_me_reader_eof_total 1503
telemt_me_idle_close_by_peer_total 1502
telemt_me_route_drop_no_conn_total 2368819
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4595967
telemt_me_endpoint_quarantine_total 689
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 764
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 23092
telemt_desync_full_logged_total 8102
telemt_desync_suppressed_total 14990
telemt_desync_frames_bucket_total{bucket="1_2"} 4386
telemt_desync_frames_bucket_total{bucket="3_10"} 8939
telemt_desync_frames_bucket_total{bucket="gt_10"} 9767
telemt_pool_swap_total 105
telemt_pool_force_close_total 3044
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 383
telemt_me_draining_writers_reap_progress_total 35375
telemt_me_writer_removed_unexpected_total 1547
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3731
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33216
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2643
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32331
telemt_me_writer_teardown_success_total{mode="normal"} 36947
telemt_me_writer_teardown_noop_total 35376
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 71083
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71896
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 72171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 72291
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 72320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 72323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 72323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 72323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 72323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 72323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 72323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 72323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 72323
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.025522
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 72323
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 383
telemt_me_refill_failed_total 4196
telemt_me_writer_restored_same_endpoint_total 1453
telemt_me_writer_restored_fallback_total 32
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7305
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 4588991
telemt_user_connections_current{user="hello"} 1446
telemt_user_octets_from_client{user="hello"} 122900969072 (114.46 GB)
telemt_user_octets_to_client{user="hello"} 1877663827670 (1.71 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 736
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 38685.8 (10h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3781105
telemt_connections_bad_total 137692
telemt_connections_current 1102
telemt_connections_me_current 1102
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1562648
telemt_upstream_connect_attempt_total 24130
telemt_upstream_connect_success_total 23977
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 24123
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15715
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8194
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 68
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_reconnect_attempts_total 45675
telemt_me_reconnect_success_total 909
telemt_me_reader_eof_total 585
telemt_me_idle_close_by_peer_total 585
telemt_me_route_drop_no_conn_total 1005415
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1834765
telemt_me_endpoint_quarantine_total 277
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 292
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10121
telemt_desync_full_logged_total 3476
telemt_desync_suppressed_total 6645
telemt_desync_frames_bucket_total{bucket="1_2"} 1798
telemt_desync_frames_bucket_total{bucket="3_10"} 3872
telemt_desync_frames_bucket_total{bucket="gt_10"} 4451
telemt_pool_swap_total 41
telemt_pool_force_close_total 1321
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 126
telemt_me_draining_writers_reap_progress_total 13469
telemt_me_writer_removed_unexpected_total 664
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1365
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12789
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1115
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12148
telemt_me_writer_teardown_success_total{mode="normal"} 14154
telemt_me_writer_teardown_noop_total 13471
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 27405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 27519
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27625
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27625
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.296180
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27625
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 126
telemt_me_refill_failed_total 2601
telemt_me_writer_restored_same_endpoint_total 816
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1838490
telemt_user_connections_current{user="hello"} 1102
telemt_user_octets_from_client{user="hello"} 53203623044 (49.55 GB)
telemt_user_octets_to_client{user="hello"} 789423307782 (735.21 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 597
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 19656.9 (5h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172079
telemt_connections_bad_total 1425
telemt_connections_current 295
telemt_connections_me_current 295
telemt_handshake_timeouts_total 4761
telemt_upstream_connect_attempt_total 9214
telemt_upstream_connect_success_total 9192
telemt_upstream_connect_fail_total 21
telemt_upstream_connect_attempts_per_request{bucket="1"} 9213
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5193
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 71
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 21
telemt_me_reconnect_attempts_total 187
telemt_me_reconnect_success_total 123
telemt_me_reader_eof_total 124
telemt_me_idle_close_by_peer_total 124
telemt_me_route_drop_no_conn_total 47966
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 151291
telemt_me_endpoint_quarantine_total 191
telemt_me_single_endpoint_shadow_rotate_total 172
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_desync_total 994
telemt_desync_full_logged_total 248
telemt_desync_suppressed_total 746
telemt_desync_frames_bucket_total{bucket="1_2"} 388
telemt_desync_frames_bucket_total{bucket="3_10"} 363
telemt_desync_frames_bucket_total{bucket="gt_10"} 243
telemt_pool_swap_total 21
telemt_pool_force_close_total 476
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 8278
telemt_me_writer_removed_unexpected_total 121
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 543
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 7859
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 7802
telemt_me_writer_teardown_success_total{mode="normal"} 8402
telemt_me_writer_teardown_noop_total 8278
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 16528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 16652
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 16670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 16680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 16680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 16680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 16680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 16680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 16680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 16680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 16680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 16680
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 16680
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.832882
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 16680
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 115
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 151005
telemt_user_connections_current{user="hello"} 295
telemt_user_octets_from_client{user="hello"} 2814070884 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 88159985312 (82.11 GB)
telemt_user_unique_ips_current{user="hello"} 136
telemt_user_unique_ips_recent_window{user="hello"} 36
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 101854.3 (28h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7122900
telemt_connections_bad_total 723834
telemt_connections_current 1639
telemt_connections_me_current 1639
telemt_handshake_timeouts_total 203213
telemt_upstream_connect_attempt_total 39337
telemt_upstream_connect_success_total 39185
telemt_upstream_connect_fail_total 115
telemt_upstream_connect_attempts_per_request{bucket="1"} 39300
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19446
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19698
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 115
telemt_me_reconnect_attempts_total 1523
telemt_me_reconnect_success_total 808
telemt_me_reader_eof_total 791
telemt_me_idle_close_by_peer_total 791
telemt_me_route_drop_no_conn_total 2106944
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5367048
telemt_me_endpoint_quarantine_total 708
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 781
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 20744
telemt_desync_full_logged_total 6931
telemt_desync_suppressed_total 13813
telemt_desync_frames_bucket_total{bucket="1_2"} 5043
telemt_desync_frames_bucket_total{bucket="3_10"} 7519
telemt_desync_frames_bucket_total{bucket="gt_10"} 8182
telemt_pool_swap_total 113
telemt_pool_force_close_total 3041
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 375
telemt_me_draining_writers_reap_progress_total 35411
telemt_me_writer_removed_unexpected_total 762
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2843
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 33349
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2953
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 32370
telemt_me_writer_teardown_success_total{mode="normal"} 36192
telemt_me_writer_teardown_noop_total 35413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 70257
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 71139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 71317
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 71517
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 71605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 71605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 71605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 71605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 71605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 71605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 71605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 71605
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 71605
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.586691
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 71605
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 375
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 719
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 35
telemt_user_connections_total{user="hello"} 5342176
telemt_user_connections_current{user="hello"} 1639
telemt_user_octets_from_client{user="hello"} 108223487864 (100.79 GB)
telemt_user_octets_to_client{user="hello"} 2503999619208 (2.28 TB)
telemt_user_unique_ips_current{user="hello"} 775
telemt_user_unique_ips_recent_window{user="hello"} 144
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 101851.0 (28h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6132175
telemt_connections_bad_total 603282
telemt_connections_current 1505
telemt_connections_me_current 1505
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 168954
telemt_upstream_connect_attempt_total 55190
telemt_upstream_connect_success_total 54774
telemt_upstream_connect_fail_total 357
telemt_upstream_connect_attempts_per_request{bucket="1"} 55131
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32231
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21410
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 357
telemt_me_reconnect_attempts_total 5427
telemt_me_reconnect_success_total 1116
telemt_me_reader_eof_total 1000
telemt_me_idle_close_by_peer_total 1000
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2160673
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4736860
telemt_me_endpoint_quarantine_total 814
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 776
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 19541
telemt_desync_full_logged_total 6568
telemt_desync_suppressed_total 12973
telemt_desync_frames_bucket_total{bucket="1_2"} 4892
telemt_desync_frames_bucket_total{bucket="3_10"} 7113
telemt_desync_frames_bucket_total{bucket="gt_10"} 7536
telemt_pool_swap_total 111
telemt_pool_force_close_total 3001
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 371
telemt_me_draining_writers_reap_progress_total 34026
telemt_me_writer_removed_unexpected_total 1010
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3330
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31753
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2778
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31025
telemt_me_writer_teardown_success_total{mode="normal"} 35083
telemt_me_writer_teardown_noop_total 34030
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 67492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 68535
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 68880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69075
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69113
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.963714
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69113
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 371
telemt_me_refill_failed_total 249
telemt_me_writer_restored_same_endpoint_total 870
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 4740051
telemt_user_connections_current{user="hello"} 1505
telemt_user_octets_from_client{user="hello"} 89505840617 (83.36 GB)
telemt_user_octets_to_client{user="hello"} 2032296660612 (1.85 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 129
```