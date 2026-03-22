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

# Server Metrics 2026-03-22 21:37:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 88245.9 (24h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3219277
telemt_connections_bad_total 236637
telemt_connections_current 856
telemt_connections_me_current 856
telemt_handshake_timeouts_total 103271
telemt_upstream_connect_attempt_total 32353
telemt_upstream_connect_success_total 32352
telemt_upstream_connect_attempts_per_request{bucket="1"} 32352
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11132
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21098
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 87
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_failed_total 4
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 1312
telemt_me_reconnect_success_total 543
telemt_me_reader_eof_total 555
telemt_me_idle_close_by_peer_total 555
telemt_me_route_drop_no_conn_total 2841138
telemt_me_route_drop_channel_closed_total 1139
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2708849
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_endpoint_quarantine_total 592
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 682
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_me_writers_warm_current 17
telemt_desync_total 11758
telemt_desync_full_logged_total 3686
telemt_desync_suppressed_total 8072
telemt_desync_frames_bucket_total{bucket="1_2"} 3183
telemt_desync_frames_bucket_total{bucket="3_10"} 4291
telemt_desync_frames_bucket_total{bucket="gt_10"} 4284
telemt_pool_swap_total 97
telemt_pool_force_close_total 3020
telemt_pool_stale_pick_total 22
telemt_me_writer_close_signal_drop_total 607
telemt_me_draining_writers_reap_progress_total 29559
telemt_me_writer_removed_unexpected_total 539
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2146
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27657
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2965
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 55
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26539
telemt_me_writer_teardown_success_total{mode="normal"} 29803
telemt_me_writer_teardown_noop_total 29570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 46968
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49122
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51158
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 54899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58934
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59373
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 333.129249
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59373
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 607
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 483
telemt_me_writer_restored_fallback_total 1
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 2698861
telemt_user_connections_current{user="hello"} 856
telemt_user_octets_from_client{user="hello"} 39330109152 (36.63 GB)
telemt_user_octets_to_client{user="hello"} 730989771972 (680.79 GB)
telemt_user_unique_ips_current{user="hello"} 381
telemt_user_unique_ips_recent_window{user="hello"} 109
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 101611.8 (28h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3907929
telemt_connections_bad_total 346202
telemt_connections_current 480
telemt_connections_me_current 480
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 99365
telemt_upstream_connect_attempt_total 60787
telemt_upstream_connect_success_total 60052
telemt_upstream_connect_fail_total 649
telemt_upstream_connect_attempts_per_request{bucket="1"} 60701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33455
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 649
telemt_me_keepalive_timeout_total 7
telemt_me_reconnect_attempts_total 6978
telemt_me_reconnect_success_total 2716
telemt_me_reader_eof_total 2664
telemt_me_idle_close_by_peer_total 2664
telemt_me_route_drop_no_conn_total 3626855
telemt_me_route_drop_channel_closed_total 37
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3116079
telemt_me_endpoint_quarantine_total 769
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 40
telemt_me_single_endpoint_outage_reconnect_success_total 39
telemt_me_single_endpoint_quarantine_bypass_total 40
telemt_me_single_endpoint_shadow_rotate_total 784
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 38
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
telemt_desync_total 12663
telemt_desync_full_logged_total 7092
telemt_desync_suppressed_total 5571
telemt_desync_frames_bucket_total{bucket="1_2"} 2863
telemt_desync_frames_bucket_total{bucket="3_10"} 4971
telemt_desync_frames_bucket_total{bucket="gt_10"} 4829
telemt_pool_swap_total 95
telemt_pool_force_close_total 2879
telemt_pool_stale_pick_total 6
telemt_me_writer_close_signal_drop_total 238
telemt_me_draining_writers_reap_progress_total 40494
telemt_me_writer_removed_unexpected_total 2605
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4918
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38203
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2452
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 427
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37615
telemt_me_writer_teardown_success_total{mode="normal"} 43121
telemt_me_writer_teardown_noop_total 40495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81674
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83230
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83616
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83616
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 14.385128
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83616
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 238
telemt_me_refill_failed_total 171
telemt_me_writer_restored_same_endpoint_total 2390
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 3126742
telemt_user_connections_current{user="hello"} 480
telemt_user_octets_from_client{user="hello"} 41470151435 (38.62 GB)
telemt_user_octets_to_client{user="hello"} 765833846926 (713.24 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 301
telemt_user_unique_ips_recent_window{user="hello"} 122
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 176471.7 (49h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16106798
telemt_connections_bad_total 1565390
telemt_connections_current 1222
telemt_connections_me_current 1222
telemt_relay_adaptive_promotions_total 19
telemt_relay_adaptive_hard_promotions_total 19
telemt_handshake_timeouts_total 394950
telemt_upstream_connect_attempt_total 78257
telemt_upstream_connect_success_total 78157
telemt_upstream_connect_fail_total 17
telemt_upstream_connect_attempts_per_request{bucket="1"} 78174
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37654
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1696
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2847
telemt_me_reconnect_success_total 1480
telemt_me_reader_eof_total 1425
telemt_me_idle_close_by_peer_total 1423
telemt_me_route_drop_no_conn_total 14016755
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12836842
telemt_me_endpoint_quarantine_total 1124
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 11
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 11
telemt_me_single_endpoint_shadow_rotate_total 1314
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_me_writers_warm_current 30
telemt_desync_total 52976
telemt_desync_full_logged_total 16734
telemt_desync_suppressed_total 36242
telemt_desync_frames_bucket_total{bucket="1_2"} 11772
telemt_desync_frames_bucket_total{bucket="3_10"} 20637
telemt_desync_frames_bucket_total{bucket="gt_10"} 20567
telemt_pool_swap_total 190
telemt_pool_force_close_total 6380
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 1031
telemt_me_draining_writers_reap_progress_total 58177
telemt_me_writer_removed_unexpected_total 1375
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5075
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 53756
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 43
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5910
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 470
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51797
telemt_me_writer_teardown_success_total{mode="normal"} 58831
telemt_me_writer_teardown_noop_total 58228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 106213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 109714
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 111418
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113740
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 116449
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 117020
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 117050
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 117051
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 117055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 117057
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 117059
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 117059
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 315.367925
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 117059
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 1031
telemt_me_refill_failed_total 75
telemt_me_writer_restored_same_endpoint_total 1279
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 88
telemt_user_connections_total{user="hello"} 12837142
telemt_user_connections_current{user="hello"} 1222
telemt_user_octets_from_client{user="hello"} 188583802941 (175.63 GB)
telemt_user_octets_to_client{user="hello"} 3441424380239 (3.13 TB)
telemt_user_msgs_from_client{user="hello"} 57811
telemt_user_msgs_to_client{user="hello"} 118217
telemt_user_unique_ips_current{user="hello"} 577
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 176473.0 (49h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11684607
telemt_connections_bad_total 1185901
telemt_connections_current 914
telemt_connections_me_current 914
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 343548
telemt_upstream_connect_attempt_total 92766
telemt_upstream_connect_success_total 91459
telemt_upstream_connect_fail_total 861
telemt_upstream_connect_attempts_per_request{bucket="1"} 92320
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 37670
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 188
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3790
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 861
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 225
telemt_me_reconnect_attempts_total 4281
telemt_me_reconnect_success_total 1789
telemt_me_reader_eof_total 1648
telemt_me_idle_close_by_peer_total 1648
telemt_me_route_drop_no_conn_total 4532538
telemt_me_route_drop_channel_closed_total 497
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8699586
telemt_me_endpoint_quarantine_total 1124
telemt_me_single_endpoint_outage_enter_total 29
telemt_me_single_endpoint_outage_exit_total 29
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 27
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 1336
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 46
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
telemt_me_writers_warm_current 30
telemt_desync_total 38459
telemt_desync_full_logged_total 12936
telemt_desync_suppressed_total 25523
telemt_desync_frames_bucket_total{bucket="1_2"} 9494
telemt_desync_frames_bucket_total{bucket="3_10"} 14791
telemt_desync_frames_bucket_total{bucket="gt_10"} 14174
telemt_pool_swap_total 187
telemt_pool_force_close_total 5757
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 706
telemt_me_draining_writers_reap_progress_total 56570
telemt_me_writer_removed_unexpected_total 1685
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5227
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52877
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5245
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 512
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 50813
telemt_me_writer_teardown_success_total{mode="normal"} 58104
telemt_me_writer_teardown_noop_total 56595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 107987
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 111179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 112324
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 113515
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 114274
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 114614
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 114689
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 114691
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 114697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 114699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 114699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 114699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 114699
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 104.214996
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 114699
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 706
telemt_me_refill_failed_total 134
telemt_me_writer_restored_same_endpoint_total 1522
telemt_me_writer_restored_fallback_total 20
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 143
telemt_user_connections_total{user="hello"} 8637490
telemt_user_connections_current{user="hello"} 914
telemt_user_octets_from_client{user="hello"} 216770540204 (201.88 GB)
telemt_user_octets_to_client{user="hello"} 3912625374899 (3.56 TB)
telemt_user_msgs_from_client{user="hello"} 124042
telemt_user_msgs_to_client{user="hello"} 140191
telemt_user_unique_ips_current{user="hello"} 397
telemt_user_unique_ips_recent_window{user="hello"} 103
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 176437.7 (49h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10923370
telemt_connections_bad_total 948541
telemt_connections_current 737
telemt_connections_me_current 737
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 344678
telemt_upstream_connect_attempt_total 76428
telemt_upstream_connect_success_total 75021
telemt_upstream_connect_fail_total 197
telemt_upstream_connect_attempts_per_request{bucket="1"} 75218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 34885
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36028
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1822
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2286
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 197
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1419
telemt_me_reconnect_attempts_total 5395
telemt_me_reconnect_success_total 2197
telemt_me_reader_eof_total 1931
telemt_me_idle_close_by_peer_total 1930
telemt_me_route_drop_no_conn_total 5312329
telemt_me_route_drop_channel_closed_total 382
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8266764
telemt_me_endpoint_quarantine_total 1211
telemt_me_single_endpoint_outage_enter_total 36
telemt_me_single_endpoint_outage_exit_total 36
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1291
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 66
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
telemt_me_writers_warm_current 2
telemt_desync_total 37839
telemt_desync_full_logged_total 12537
telemt_desync_suppressed_total 25302
telemt_desync_frames_bucket_total{bucket="1_2"} 9561
telemt_desync_frames_bucket_total{bucket="3_10"} 14473
telemt_desync_frames_bucket_total{bucket="gt_10"} 13805
telemt_pool_swap_total 184
telemt_pool_force_close_total 5698
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 723
telemt_me_draining_writers_reap_progress_total 56705
telemt_me_writer_removed_unexpected_total 2083
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5827
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 52885
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 25
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5133
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 565
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 51007
telemt_me_writer_teardown_success_total{mode="normal"} 58712
telemt_me_writer_teardown_noop_total 56776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 109718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 112400
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 113344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 114411
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 115007
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 115221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 115349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 115380
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 115388
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 115401
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 115434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 115437
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 115488
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3174.216203
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 115488
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 723
telemt_me_refill_failed_total 169
telemt_me_writer_restored_same_endpoint_total 1897
telemt_me_writer_restored_fallback_total 15
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 68
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 8258790
telemt_user_connections_current{user="hello"} 737
telemt_user_octets_from_client{user="hello"} 191833243837 (178.66 GB)
telemt_user_octets_to_client{user="hello"} 3435437353385 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 337
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 46717.3 (12h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11007148
telemt_connections_bad_total 666726
telemt_connections_current 1354
telemt_connections_me_current 1354
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 246181
telemt_upstream_connect_attempt_total 50442
telemt_upstream_connect_success_total 47903
telemt_upstream_connect_fail_total 1735
telemt_upstream_connect_attempts_per_request{bucket="1"} 49638
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24613
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1516
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5984
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1735
telemt_me_keepalive_timeout_total 975
telemt_me_reconnect_attempts_total 7006
telemt_me_reconnect_success_total 1027
telemt_me_reader_eof_total 635
telemt_me_idle_close_by_peer_total 634
telemt_me_route_drop_no_conn_total 25247251
telemt_me_route_drop_channel_closed_total 56
telemt_me_route_drop_queue_full_total 27
telemt_me_route_drop_queue_full_profile_total{profile="high"} 27
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9141030
telemt_me_endpoint_quarantine_total 322
telemt_me_single_endpoint_outage_enter_total 76
telemt_me_single_endpoint_outage_exit_total 76
telemt_me_single_endpoint_outage_reconnect_attempt_total 135
telemt_me_single_endpoint_outage_reconnect_success_total 41
telemt_me_single_endpoint_quarantine_bypass_total 135
telemt_me_single_endpoint_shadow_rotate_total 369
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
telemt_me_writers_active_current 44
telemt_desync_total 15516
telemt_desync_full_logged_total 4114
telemt_desync_suppressed_total 11402
telemt_desync_frames_bucket_total{bucket="1_2"} 2960
telemt_desync_frames_bucket_total{bucket="3_10"} 6283
telemt_desync_frames_bucket_total{bucket="gt_10"} 6273
telemt_pool_swap_total 47
telemt_pool_force_close_total 1665
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 448
telemt_me_draining_writers_reap_progress_total 13624
telemt_me_writer_removed_unexpected_total 914
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1996
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12498
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 9
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1359
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11959
telemt_me_writer_teardown_success_total{mode="normal"} 14494
telemt_me_writer_teardown_noop_total 13643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 24489
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26103
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 27592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 28081
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 28137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 28137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 28137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 28137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 28137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 28137
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 28137
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 52.122445
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 28137
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 448
telemt_me_refill_failed_total 325
telemt_me_writer_restored_same_endpoint_total 667
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 96
telemt_me_async_recovery_trigger_total 3149
telemt_me_writer_removed_unexpected_minus_restored_total 241
telemt_user_connections_total{user="hello"} 9165752
telemt_user_connections_current{user="hello"} 1354
telemt_user_octets_from_client{user="hello"} 85068810564 (79.23 GB)
telemt_user_octets_to_client{user="hello"} 547818091354 (510.20 GB)
telemt_user_msgs_from_client{user="hello"} 65206
telemt_user_msgs_to_client{user="hello"} 53386
telemt_user_unique_ips_current{user="hello"} 535
telemt_user_unique_ips_recent_window{user="hello"} 183
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 176443.6 (49h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10833429
telemt_connections_bad_total 912370
telemt_connections_current 1093
telemt_connections_me_current 1093
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 238129
telemt_upstream_connect_attempt_total 105279
telemt_upstream_connect_success_total 104178
telemt_upstream_connect_fail_total 936
telemt_upstream_connect_attempts_per_request{bucket="1"} 105114
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 63094
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39493
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 238
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1353
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 936
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 72535
telemt_me_reconnect_success_total 2868
telemt_me_reader_eof_total 2564
telemt_me_idle_close_by_peer_total 2562
telemt_me_route_drop_no_conn_total 5232102
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8562834
telemt_me_endpoint_quarantine_total 1161
telemt_me_single_endpoint_outage_enter_total 40
telemt_me_single_endpoint_outage_exit_total 40
telemt_me_single_endpoint_outage_reconnect_attempt_total 42
telemt_me_single_endpoint_outage_reconnect_success_total 40
telemt_me_single_endpoint_quarantine_bypass_total 42
telemt_me_single_endpoint_shadow_rotate_total 1319
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 11
telemt_desync_total 45678
telemt_desync_full_logged_total 15608
telemt_desync_suppressed_total 30070
telemt_desync_frames_bucket_total{bucket="1_2"} 9259
telemt_desync_frames_bucket_total{bucket="3_10"} 17486
telemt_desync_frames_bucket_total{bucket="gt_10"} 18933
telemt_pool_swap_total 180
telemt_pool_force_close_total 5371
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 646
telemt_me_draining_writers_reap_progress_total 60571
telemt_me_writer_removed_unexpected_total 2599
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6372
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56827
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4641
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 730
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55200
telemt_me_writer_teardown_success_total{mode="normal"} 63199
telemt_me_writer_teardown_noop_total 60572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 121644
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 123035
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 123454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 123727
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123771
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.139956
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123771
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 646
telemt_me_refill_failed_total 4291
telemt_me_writer_restored_same_endpoint_total 2414
telemt_me_writer_restored_fallback_total 48
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7367
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 8565944
telemt_user_connections_current{user="hello"} 1093
telemt_user_octets_from_client{user="hello"} 193396582985 (180.11 GB)
telemt_user_octets_to_client{user="hello"} 3266106800740 (2.97 TB)
telemt_user_msgs_from_client{user="hello"} 160634
telemt_user_msgs_to_client{user="hello"} 619200
telemt_user_unique_ips_current{user="hello"} 476
telemt_user_unique_ips_recent_window{user="hello"} 129
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 113279.9 (31h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11456423
telemt_connections_bad_total 458709
telemt_connections_current 821
telemt_connections_me_current 821
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 4693962
telemt_upstream_connect_attempt_total 53474
telemt_upstream_connect_success_total 53079
telemt_upstream_connect_fail_total 385
telemt_upstream_connect_attempts_per_request{bucket="1"} 53464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28924
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23952
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 203
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 385
telemt_me_reconnect_attempts_total 48662
telemt_me_reconnect_success_total 1702
telemt_me_reader_eof_total 1363
telemt_me_idle_close_by_peer_total 1362
telemt_me_route_drop_no_conn_total 4064493
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5526618
telemt_me_endpoint_quarantine_total 735
telemt_me_single_endpoint_outage_enter_total 19
telemt_me_single_endpoint_outage_exit_total 19
telemt_me_single_endpoint_outage_reconnect_attempt_total 59
telemt_me_single_endpoint_outage_reconnect_success_total 19
telemt_me_single_endpoint_quarantine_bypass_total 59
telemt_me_single_endpoint_shadow_rotate_total 856
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
telemt_me_writers_active_current 45
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 31033
telemt_desync_full_logged_total 10560
telemt_desync_suppressed_total 20473
telemt_desync_frames_bucket_total{bucket="1_2"} 6164
telemt_desync_frames_bucket_total{bucket="3_10"} 12269
telemt_desync_frames_bucket_total{bucket="gt_10"} 12600
telemt_pool_swap_total 119
telemt_pool_force_close_total 3619
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 361
telemt_me_draining_writers_reap_progress_total 39647
telemt_me_writer_removed_unexpected_total 1421
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3435
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 37669
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3178
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 441
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36028
telemt_me_writer_teardown_success_total{mode="normal"} 41104
telemt_me_writer_teardown_noop_total 39654
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 79479
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80531
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 80758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 80758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80758
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80758
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 8.618866
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80758
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 361
telemt_me_refill_failed_total 2729
telemt_me_writer_restored_same_endpoint_total 1512
telemt_me_writer_restored_fallback_total 19
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4332
telemt_user_connections_total{user="hello"} 5519295
telemt_user_connections_current{user="hello"} 821
telemt_user_octets_from_client{user="hello"} 118221036664 (110.10 GB)
telemt_user_octets_to_client{user="hello"} 2118873423886 (1.93 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 389
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 94250.7 (26h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1426093
telemt_connections_bad_total 35296
telemt_connections_current 754
telemt_connections_me_current 754
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 27090
telemt_upstream_connect_attempt_total 44121
telemt_upstream_connect_success_total 43984
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 44094
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19827
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23402
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 755
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2050
telemt_me_reconnect_success_total 835
telemt_me_reader_eof_total 817
telemt_me_idle_close_by_peer_total 817
telemt_me_route_drop_no_conn_total 495416
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1265701
telemt_me_endpoint_quarantine_total 763
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 775
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
telemt_me_writers_active_current 44
telemt_desync_total 7880
telemt_desync_full_logged_total 2400
telemt_desync_suppressed_total 5480
telemt_desync_frames_bucket_total{bucket="1_2"} 1898
telemt_desync_frames_bucket_total{bucket="3_10"} 3039
telemt_desync_frames_bucket_total{bucket="gt_10"} 2943
telemt_pool_swap_total 101
telemt_pool_force_close_total 2630
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 148
telemt_me_draining_writers_reap_progress_total 36885
telemt_me_writer_removed_unexpected_total 787
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2913
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 34792
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2542
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34255
telemt_me_writer_teardown_success_total{mode="normal"} 37705
telemt_me_writer_teardown_noop_total 36889
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 73712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 74329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 74557
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 74594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 74594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 74594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 74594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 74594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 74594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 74594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 74594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 74594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 74594
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.888334
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 74594
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 148
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 708
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 1261664
telemt_user_connections_current{user="hello"} 754
telemt_user_octets_from_client{user="hello"} 24534126877 (22.85 GB)
telemt_user_octets_to_client{user="hello"} 535221802483 (498.46 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 265
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 176448.2 (49h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13167433
telemt_connections_bad_total 1560126
telemt_connections_current 1019
telemt_connections_me_current 1019
telemt_handshake_timeouts_total 378089
telemt_upstream_connect_attempt_total 67184
telemt_upstream_connect_success_total 66846
telemt_upstream_connect_fail_total 201
telemt_upstream_connect_attempts_per_request{bucket="1"} 67047
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 33122
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33622
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 98
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 201
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 2630
telemt_me_reconnect_success_total 1371
telemt_me_reader_eof_total 1339
telemt_me_idle_close_by_peer_total 1339
telemt_me_route_drop_no_conn_total 4462341
telemt_me_route_drop_channel_closed_total 123
telemt_me_route_drop_queue_full_total 41
telemt_me_route_drop_queue_full_profile_total{profile="high"} 41
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9951630
telemt_me_endpoint_quarantine_total 1197
telemt_me_kdf_drift_total 2
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 11
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 1322
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
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 13
telemt_desync_total 41524
telemt_desync_full_logged_total 13538
telemt_desync_suppressed_total 27986
telemt_desync_frames_bucket_total{bucket="1_2"} 9983
telemt_desync_frames_bucket_total{bucket="3_10"} 15288
telemt_desync_frames_bucket_total{bucket="gt_10"} 16253
telemt_pool_swap_total 195
telemt_pool_force_close_total 5337
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 657
telemt_me_draining_writers_reap_progress_total 60568
telemt_me_writer_removed_unexpected_total 1288
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4906
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56991
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 5163
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 174
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55231
telemt_me_writer_teardown_success_total{mode="normal"} 61897
telemt_me_writer_teardown_noop_total 60570
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 119909
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 121575
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 121958
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 122454
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 122467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 122467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 122467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 122467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 122467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 122467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 122467
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 122467
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.547331
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 122467
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 657
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 1199
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 9918504
telemt_user_connections_current{user="hello"} 1019
telemt_user_octets_from_client{user="hello"} 193715253576 (180.41 GB)
telemt_user_octets_to_client{user="hello"} 4389275712468 (3.99 TB)
telemt_user_unique_ips_current{user="hello"} 416
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 176444.8 (49h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11451186
telemt_connections_bad_total 1302549
telemt_connections_current 910
telemt_connections_me_current 910
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 301977
telemt_upstream_connect_attempt_total 93617
telemt_upstream_connect_success_total 92780
telemt_upstream_connect_fail_total 630
telemt_upstream_connect_attempts_per_request{bucket="1"} 93410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 39148
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 913
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2065
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 630
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 9985
telemt_me_reconnect_success_total 2412
telemt_me_reader_eof_total 2253
telemt_me_idle_close_by_peer_total 2252
telemt_me_seq_mismatch_total 82
telemt_me_route_drop_no_conn_total 5621649
telemt_me_route_drop_channel_closed_total 354
telemt_me_route_drop_queue_full_total 19
telemt_me_route_drop_queue_full_profile_total{profile="high"} 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8852710
telemt_me_endpoint_quarantine_total 1350
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 49
telemt_me_single_endpoint_outage_exit_total 49
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 1321
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_me_writers_warm_current 11
telemt_desync_total 41073
telemt_desync_full_logged_total 13163
telemt_desync_suppressed_total 27910
telemt_desync_frames_bucket_total{bucket="1_2"} 10534
telemt_desync_frames_bucket_total{bucket="3_10"} 15125
telemt_desync_frames_bucket_total{bucket="gt_10"} 15414
telemt_pool_swap_total 185
telemt_pool_force_close_total 5133
telemt_pool_stale_pick_total 360
telemt_me_writer_close_signal_drop_total 644
telemt_me_draining_writers_reap_progress_total 60323
telemt_me_writer_removed_unexpected_total 2286
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 6236
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 56451
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4662
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 471
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 55190
telemt_me_writer_teardown_success_total{mode="normal"} 62687
telemt_me_writer_teardown_noop_total 60328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 120357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 122110
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 122646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 122965
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 123015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 123015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 123015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 123015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 123015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 123015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 123015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 123015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 123015
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 17.267757
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 123015
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 644
telemt_me_refill_failed_total 391
telemt_me_writer_restored_same_endpoint_total 1961
telemt_me_writer_restored_fallback_total 114
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 133
telemt_me_writer_removed_unexpected_minus_restored_total 211
telemt_user_connections_total{user="hello"} 8858174
telemt_user_connections_current{user="hello"} 910
telemt_user_octets_from_client{user="hello"} 156512564017 (145.76 GB)
telemt_user_octets_to_client{user="hello"} 3447071862791 (3.14 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 379
telemt_user_unique_ips_recent_window{user="hello"} 87
```